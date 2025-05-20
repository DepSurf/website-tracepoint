# Tracepoint: <code>iocost_ioc_vrate_adj</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    int nr_surpluses;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    int nr_surpluses;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
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
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    int nr_surpluses;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    int nr_surpluses;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    int nr_surpluses;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    int nr_surpluses;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
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
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    int nr_surpluses;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    int nr_surpluses;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    int nr_surpluses;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_ioc_vrate_adj {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u64 old_vrate;
    u64 new_vrate;
    int busy_level;
    u32 read_missed_ppm;
    u32 write_missed_ppm;
    u32 rq_wait_pct;
    int nr_lagging;
    int nr_shortages;
    int nr_surpluses;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param type changed. </b>
<code>u32[2] *missed_ppm</code> ➡️ <code>u32 *missed_ppm</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field removed. </b>
<code>int nr_surpluses</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param removed. </b>
<code>int nr_surpluses</code>
</li>
</ul>
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
