# Tracepoint: <code>iocost_inuse_takeback</code>

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
struct trace_event_raw_iocg_inuse_update {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u32 old_inuse;
    u32 new_inuse;
    u64 old_hweight_inuse;
    u64 new_hweight_inuse;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocg_inuse_update(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 old_inuse, u32 new_inuse, u64 old_hw_inuse, u64 new_hw_inuse);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocg_inuse_update {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u32 old_inuse;
    u32 new_inuse;
    u64 old_hweight_inuse;
    u64 new_hweight_inuse;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocg_inuse_update(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 old_inuse, u32 new_inuse, u64 old_hw_inuse, u64 new_hw_inuse);
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocg_inuse_update {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u32 old_inuse;
    u32 new_inuse;
    u64 old_hweight_inuse;
    u64 new_hweight_inuse;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocg_inuse_update(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 old_inuse, u32 new_inuse, u64 old_hw_inuse, u64 new_hw_inuse);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocg_inuse_update {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u32 old_inuse;
    u32 new_inuse;
    u64 old_hweight_inuse;
    u64 new_hweight_inuse;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocg_inuse_update(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 old_inuse, u32 new_inuse, u64 old_hw_inuse, u64 new_hw_inuse);
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocg_inuse_update {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u32 old_inuse;
    u32 new_inuse;
    u64 old_hweight_inuse;
    u64 new_hweight_inuse;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocg_inuse_update(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 old_inuse, u32 new_inuse, u64 old_hw_inuse, u64 new_hw_inuse);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocg_inuse_update {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u32 old_inuse;
    u32 new_inuse;
    u64 old_hweight_inuse;
    u64 new_hweight_inuse;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocg_inuse_update(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 old_inuse, u32 new_inuse, u64 old_hw_inuse, u64 new_hw_inuse);
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
struct trace_event_raw_iocg_inuse_update {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u32 old_inuse;
    u32 new_inuse;
    u64 old_hweight_inuse;
    u64 new_hweight_inuse;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocg_inuse_update(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 old_inuse, u32 new_inuse, u64 old_hw_inuse, u64 new_hw_inuse);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocg_inuse_update {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u32 old_inuse;
    u32 new_inuse;
    u64 old_hweight_inuse;
    u64 new_hweight_inuse;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocg_inuse_update(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 old_inuse, u32 new_inuse, u64 old_hw_inuse, u64 new_hw_inuse);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocg_inuse_update {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u32 old_inuse;
    u32 new_inuse;
    u64 old_hweight_inuse;
    u64 new_hweight_inuse;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocg_inuse_update(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 old_inuse, u32 new_inuse, u64 old_hw_inuse, u64 new_hw_inuse);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_iocg_inuse_update {
    struct trace_entry ent;
    u32 __data_loc_devname;
    u32 __data_loc_cgroup;
    u64 now;
    u32 old_inuse;
    u32 new_inuse;
    u64 old_hweight_inuse;
    u64 new_hweight_inuse;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_iocg_inuse_update(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u32 old_inuse, u32 new_inuse, u64 old_hw_inuse, u64 new_hw_inuse);
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
