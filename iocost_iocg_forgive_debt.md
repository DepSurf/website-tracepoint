# Tracepoint: <code>iocost_iocg_forgive_debt</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_iocg_forgive_debt {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u64 vnow;
    u32 usage_pct;
    u64 old_debt;
    u64 new_debt;
    u64 old_delay;
    u64 new_delay;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_iocg_forgive_debt(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 usage_pct, u64 old_debt, u64 new_debt, u64 old_delay, u64 new_delay);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_iocg_forgive_debt {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u64 vnow;
    u32 usage_pct;
    u64 old_debt;
    u64 new_debt;
    u64 old_delay;
    u64 new_delay;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_iocg_forgive_debt(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 usage_pct, u64 old_debt, u64 new_debt, u64 old_delay, u64 new_delay);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_iocg_forgive_debt {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u64 vnow;
    u32 usage_pct;
    u64 old_debt;
    u64 new_debt;
    u64 old_delay;
    u64 new_delay;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_iocg_forgive_debt(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 usage_pct, u64 old_debt, u64 new_debt, u64 old_delay, u64 new_delay);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_iocg_forgive_debt {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u64 vnow;
    u32 usage_pct;
    u64 old_debt;
    u64 new_debt;
    u64 old_delay;
    u64 new_delay;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_iocg_forgive_debt(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 usage_pct, u64 old_debt, u64 new_debt, u64 old_delay, u64 new_delay);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_iocg_forgive_debt {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u64 vnow;
    u32 usage_pct;
    u64 old_debt;
    u64 new_debt;
    u64 old_delay;
    u64 new_delay;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_iocg_forgive_debt(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 usage_pct, u64 old_debt, u64 new_debt, u64 old_delay, u64 new_delay);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_iocg_forgive_debt {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u64 vnow;
    u32 usage_pct;
    u64 old_debt;
    u64 new_debt;
    u64 old_delay;
    u64 new_delay;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_iocg_forgive_debt(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 usage_pct, u64 old_debt, u64 new_debt, u64 old_delay, u64 new_delay);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocost_iocg_forgive_debt {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u64 vnow;
    u32 usage_pct;
    u64 old_debt;
    u64 new_debt;
    u64 old_delay;
    u64 new_delay;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocost_iocg_forgive_debt(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 usage_pct, u64 old_debt, u64 new_debt, u64 old_delay, u64 new_delay);
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
