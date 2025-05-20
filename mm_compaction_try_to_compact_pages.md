# Tracepoint: <code>mm_compaction_try_to_compact_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    enum migrate_mode mode;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, enum migrate_mode mode);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    long unsigned int gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    long unsigned int gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    long unsigned int gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    long unsigned int gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
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
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
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
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_compaction_try_to_compact_pages {
    struct trace_entry ent;
    int order;
    gfp_t gfp_mask;
    int prio;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_compaction_try_to_compact_pages(void *__data, int order, gfp_t gfp_mask, int prio);
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
<b>Field added. </b>
<code>int prio</code>
</li>
<li>
<b>Field removed. </b>
<code>enum migrate_mode mode</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>int prio</code>
</li>
<li>
<b>Param removed. </b>
<code>enum migrate_mode mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field type changed. </b>
<code>gfp_t gfp_mask</code> ➡️ <code>long unsigned int gfp_mask</code>
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
