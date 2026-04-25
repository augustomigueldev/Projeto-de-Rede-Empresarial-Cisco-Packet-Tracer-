<h1 align="center">🚀 Projeto de Rede Empresarial - Cisco Packet Tracer</h1>

<p align="center">
Simulação de uma infraestrutura de rede com duas LANs, roteamento entre redes, servidor interno e NAT/PAT para acesso externo.
</p>

---

## 📌 Visão Geral

Este projeto simula uma pequena rede empresarial utilizando o Cisco Packet Tracer.  
Foram configuradas duas redes locais, comunicação entre LANs, servidor interno e tradução de endereços com NAT/PAT.

---

## 🧱 Topologia

| Item | Quantidade |
|---|---:|
| LANs | 2 |
| Switches | 2 |
| Roteadores | 2 |
| PCs | 4 |
| Servidor interno | 1 |
| Servidor externo / Internet simulada | 1 |

---

## 🌐 Endereçamento IP

| Rede | Endereço | Gateway |
|---|---|---|
| LAN 1 - Administração | `192.168.10.0/24` | `192.168.10.1` |
| LAN 2 - Funcionários | `192.168.20.0/24` | `192.168.20.1` |
| Rede Externa | `200.0.0.0/24` | `200.0.0.1` |

---

## 🔧 Configurações Realizadas

- Roteamento entre redes usando o Router0
- Comunicação entre LAN 1 e LAN 2
- Servidor interno com HTTP
- NAT/PAT para simular acesso externo
- Segundo roteador simulando rede externa
- Testes com `ping` e `show ip nat translations`

---

## 🔍 Testes Realizados

### Comunicação entre redes

```bash
ping 192.168.20.10
