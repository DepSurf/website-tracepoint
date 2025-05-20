# Tracepoint: <code>mm_shrink_slab_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int pgs_scanned;
    long unsigned int lru_pgs;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int pgs_scanned, long unsigned int lru_pgs, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int pgs_scanned;
    long unsigned int lru_pgs;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int pgs_scanned, long unsigned int lru_pgs, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int pgs_scanned;
    long unsigned int lru_pgs;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int pgs_scanned, long unsigned int lru_pgs, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int pgs_scanned;
    long unsigned int lru_pgs;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int pgs_scanned, long unsigned int lru_pgs, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int pgs_scanned;
    long unsigned int lru_pgs;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int pgs_scanned, long unsigned int lru_pgs, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    long unsigned int gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    long unsigned int gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    long unsigned int gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    long unsigned int gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
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
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
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
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_shrink_slab_start {
    struct trace_entry ent;
    struct shrinker *shr;
    void *shrink;
    int nid;
    long int nr_objects_to_shrink;
    gfp_t gfp_flags;
    long unsigned int cache_items;
    long long unsigned int delta;
    long unsigned int total_scan;
    int priority;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_shrink_slab_start(void *__data, struct shrinker *shr, struct shrink_control *sc, long int nr_objects_to_shrink, long unsigned int cache_items, long long unsigned int delta, long unsigned int total_scan, int priority);
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field added. </b>
<code>int priority</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int pgs_scanned</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int lru_pgs</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>int priority</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int pgs_scanned</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int lru_pgs</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, shr, sc, nr_objects_to_shrink, pgs_scanned, lru_pgs, cache_items, delta, total_scan</code> ➡️ <code>__data, shr, sc, nr_objects_to_shrink, cache_items, delta, total_scan, priority</code>
</li>
</ul>
</details>
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
<code>gfp_t gfp_flags</code> ➡️ <code>long unsigned int gfp_flags</code>
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
