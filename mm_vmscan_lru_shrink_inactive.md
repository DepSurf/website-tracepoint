# Tracepoint: <code>mm_vmscan_lru_shrink_inactive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    int zid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, int zid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, int priority, int reclaim_flags);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    long unsigned int nr_activate;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, long unsigned int nr_dirty, long unsigned int nr_writeback, long unsigned int nr_congested, long unsigned int nr_immediate, long unsigned int nr_activate, long unsigned int nr_ref_keep, long unsigned int nr_unmap_fail, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    long unsigned int nr_activate;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, long unsigned int nr_dirty, long unsigned int nr_writeback, long unsigned int nr_congested, long unsigned int nr_immediate, long unsigned int nr_activate, long unsigned int nr_ref_keep, long unsigned int nr_unmap_fail, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    long unsigned int nr_activate;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    long unsigned int nr_activate;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
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
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
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
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_vmscan_lru_shrink_inactive {
    struct trace_entry ent;
    int nid;
    long unsigned int nr_scanned;
    long unsigned int nr_reclaimed;
    long unsigned int nr_dirty;
    long unsigned int nr_writeback;
    long unsigned int nr_congested;
    long unsigned int nr_immediate;
    unsigned int nr_activate0;
    unsigned int nr_activate1;
    long unsigned int nr_ref_keep;
    long unsigned int nr_unmap_fail;
    int priority;
    int reclaim_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_vmscan_lru_shrink_inactive(void *__data, int nid, long unsigned int nr_scanned, long unsigned int nr_reclaimed, struct reclaim_stat *stat, int priority, int file);
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field removed. </b>
<code>int zid</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>int file</code>
</li>
<li>
<b>Param removed. </b>
<code>int zid</code>
</li>
<li>
<b>Param removed. </b>
<code>int reclaim_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, nid, zid, nr_scanned, nr_reclaimed, priority, reclaim_flags</code> ➡️ <code>__data, nid, nr_scanned, nr_reclaimed, priority, file</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nr_dirty</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nr_writeback</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nr_congested</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nr_immediate</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nr_activate</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nr_ref_keep</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nr_unmap_fail</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int nr_dirty</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int nr_writeback</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int nr_congested</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int nr_immediate</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int nr_activate</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int nr_ref_keep</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int nr_unmap_fail</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, nid, nr_scanned, nr_reclaimed, priority, file</code> ➡️ <code>__data, nid, nr_scanned, nr_reclaimed, nr_dirty, nr_writeback, nr_congested, nr_immediate, nr_activate, nr_ref_keep, nr_unmap_fail, priority, file</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>struct reclaim_stat *stat</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_dirty</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_writeback</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_congested</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_immediate</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_activate</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_ref_keep</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_unmap_fail</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, nid, nr_scanned, nr_reclaimed, nr_dirty, nr_writeback, nr_congested, nr_immediate, nr_activate, nr_ref_keep, nr_unmap_fail, priority, file</code> ➡️ <code>__data, nid, nr_scanned, nr_reclaimed, stat, priority, file</code>
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
<b>Event changed. </b>
</li>
<li>
<b>Field added. </b>
<code>unsigned int nr_activate0</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int nr_activate1</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int nr_activate</code>
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
