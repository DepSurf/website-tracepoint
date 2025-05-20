# Tracepoint: <code>track_foreign_dirty</code>

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
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    long unsigned int ino;
    unsigned int memcg_id;
    unsigned int cgroup_ino;
    unsigned int page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    ino_t ino;
    unsigned int memcg_id;
    ino_t cgroup_ino;
    ino_t page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    ino_t ino;
    unsigned int memcg_id;
    ino_t cgroup_ino;
    ino_t page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    ino_t ino;
    unsigned int memcg_id;
    ino_t cgroup_ino;
    ino_t page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    ino_t ino;
    unsigned int memcg_id;
    ino_t cgroup_ino;
    ino_t page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    ino_t ino;
    unsigned int memcg_id;
    ino_t cgroup_ino;
    ino_t page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct folio *folio, struct bdi_writeback *wb);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    ino_t ino;
    unsigned int memcg_id;
    ino_t cgroup_ino;
    ino_t page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct folio *folio, struct bdi_writeback *wb);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    ino_t ino;
    unsigned int memcg_id;
    ino_t cgroup_ino;
    ino_t page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct folio *folio, struct bdi_writeback *wb);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    ino_t ino;
    unsigned int memcg_id;
    ino_t cgroup_ino;
    ino_t page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct folio *folio, struct bdi_writeback *wb);
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
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    long unsigned int ino;
    unsigned int memcg_id;
    unsigned int cgroup_ino;
    unsigned int page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    long unsigned int ino;
    unsigned int memcg_id;
    unsigned int cgroup_ino;
    unsigned int page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    long unsigned int ino;
    unsigned int memcg_id;
    unsigned int cgroup_ino;
    unsigned int page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    long unsigned int ino;
    unsigned int memcg_id;
    unsigned int cgroup_ino;
    unsigned int page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
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
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    long unsigned int ino;
    unsigned int memcg_id;
    unsigned int cgroup_ino;
    unsigned int page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    long unsigned int ino;
    unsigned int memcg_id;
    unsigned int cgroup_ino;
    unsigned int page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    long unsigned int ino;
    unsigned int memcg_id;
    unsigned int cgroup_ino;
    unsigned int page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_track_foreign_dirty {
    struct trace_entry ent;
    char name[32];
    u64 bdi_id;
    long unsigned int ino;
    unsigned int memcg_id;
    unsigned int cgroup_ino;
    unsigned int page_cgroup_ino;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_track_foreign_dirty(void *__data, struct page *page, struct bdi_writeback *wb);
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
<b>Event changed. </b>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int ino</code> ➡️ <code>ino_t ino</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int cgroup_ino</code> ➡️ <code>ino_t cgroup_ino</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int page_cgroup_ino</code> ➡️ <code>ino_t page_cgroup_ino</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
