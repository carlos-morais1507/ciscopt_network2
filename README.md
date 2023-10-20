# Cisco Packet Tracer Project 2 - Subnetting Basics
**Made by:** Carlos Alberto Morais Junior
<br>
**Date:** 10-19-2023

![image](https://github.com/carlos-morais1507/ciscopt_network2/assets/105527392/26a24f9c-580c-404d-a82c-035272e6b603)

## Network Components

### Router0
**Device Name:** Router0
<br>
**Device Model:** 1941
<br>
**Hostname:** Router

| Port | Link | IP Address | Subnet Mask
|---|---|---|---|
|G0/0|Up|192.168.0.62/26|255.255.255.192|
|G0/1|Up|192.168.0.65/26|255.255.255.192|

### Router1
**Device Name:** Router1
<br>
**Device Model:** 1941
<br>
**Hostname:** Router

| Port | Link | IP Address | Subnet Mask
|---|---|---|---|
|G0/0|Up|192.168.0.190/26|255.255.255.192|
|G0/1|Up|192.168.0.66/26|255.255.255.192|

### Switch0
**Device Name:** Switch0
<br>
**Device Model:** 2960-24TT
<br>
**Hostname:** Switch

| Port | Link | IP Address | Subnet Mask
|---|---|:-:|:-:|
|G0/1|Up|- -|- -|
|F0/1|Up|- -|- -|

### Switch1
**Device Name:** Switch1
<br>
**Device Model:** 2960-24TT
<br>
**Hostname:** Switch

| Port | Link | IP Address | Subnet Mask
|---|---|:-:|:-:|
|G0/1|Up|- -|- -|
|F0/1|Up|- -|- -|

### PC0
**Device Name:** PC0
<br>
**Device Model:** PC-PT

| Port | Link | IP Address | Subnet Mask
|---|---|---|---|
|F0/0|Up|192.168.0.1/26|255.255.255.192|

**Gateway:** 192.168.0.62

### PC1
**Device Name:** PC1
<br>
**Device Model:** PC-PT

| Port | Link | IP Address | Subnet Mask
|---|---|---|---|
|F0/0|Up|192.168.0.129/26|255.255.255.192|

**Gateway:** 192.168.0.190

> All Links except for Router0 - Router1 were made with the Copper Straight-Through Cable. 
> Router0 - Router1 was made with Copper Cross-Over Cable

## Simple UDP Tests
| Status | Source | Destination | Type | Time (sec) | Num |
|---|---|---|---|---|---|
|Successful|PC0|PC1|ICMP|0.000|0|
