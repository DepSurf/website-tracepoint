# Tracepoint: <code>mm_migrate_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    long unsigned int thp_succeeded;
    long unsigned int thp_failed;
    long unsigned int thp_split;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    long unsigned int thp_succeeded;
    long unsigned int thp_failed;
    long unsigned int thp_split;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    long unsigned int thp_succeeded;
    long unsigned int thp_failed;
    long unsigned int thp_split;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    long unsigned int thp_succeeded;
    long unsigned int thp_failed;
    long unsigned int thp_split;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    long unsigned int thp_succeeded;
    long unsigned int thp_failed;
    long unsigned int thp_split;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    long unsigned int thp_succeeded;
    long unsigned int thp_failed;
    long unsigned int thp_split;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    long unsigned int thp_succeeded;
    long unsigned int thp_failed;
    long unsigned int thp_split;
    long unsigned int large_folio_split;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, long unsigned int large_folio_split, enum migrate_mode mode, int reason);
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
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
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
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_mm_migrate_pages {
    struct trace_entry ent;
    long unsigned int succeeded;
    long unsigned int failed;
    enum migrate_mode mode;
    int reason;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, enum migrate_mode mode, int reason);
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int thp_succeeded</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int thp_failed</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int thp_split</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int thp_succeeded</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int thp_failed</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int thp_split</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, succeeded, failed, mode, reason</code> ➡️ <code>__data, succeeded, failed, thp_succeeded, thp_failed, thp_split, mode, reason</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int large_folio_split</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int large_folio_split</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, succeeded, failed, thp_succeeded, thp_failed, thp_split, mode, reason</code> ➡️ <code>__data, succeeded, failed, thp_succeeded, thp_failed, thp_split, large_folio_split, mode, reason</code>
</li>
</ul>
</details>
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
