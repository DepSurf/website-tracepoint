# Tracepoint: <code>fib6_table_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct rt6_info *rt, u32 tb_id, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct rt6_info *rt, u32 tb_id, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct rt6_info *rt, u32 tb_id, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct rt6_info *rt, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_info *f6i, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_info *f6i, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    char name[16];
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    char name[16];
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    char name[16];
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_fib6_table_lookup {
    struct trace_entry ent;
    u32 tb_id;
    int err;
    int oif;
    int iif;
    __u8 tos;
    __u8 scope;
    __u8 flags;
    __u8 src[16];
    __u8 dst[16];
    u16 sport;
    u16 dport;
    u8 proto;
    u8 rt_type;
    u32 __data_loc_name;
    __u8 gw[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_fib6_table_lookup(void *__data, const struct net *net, const struct fib6_result *res, struct fib6_table *table, const struct flowi6 *flp);
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>struct fib6_table *table</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 tb_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field added. </b>
<code>int err</code>
</li>
<li>
<b>Field added. </b>
<code>u16 sport</code>
</li>
<li>
<b>Field added. </b>
<code>u16 dport</code>
</li>
<li>
<b>Field added. </b>
<code>u8 proto</code>
</li>
<li>
<b>Field added. </b>
<code>u8 rt_type</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>const struct fib6_info *f6i</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct rt6_info *rt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>const struct fib6_result *res</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct fib6_info *f6i</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field added. </b>
<code>char name[16]</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 __data_loc_name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
