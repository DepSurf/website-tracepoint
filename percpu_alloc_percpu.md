# Tracepoint: <code>percpu_alloc_percpu</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    long unsigned int call_site;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    size_t bytes_alloc;
    long unsigned int gfp_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, long unsigned int call_site, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr, size_t bytes_alloc, gfp_t gfp_flags);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    long unsigned int call_site;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    size_t bytes_alloc;
    long unsigned int gfp_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, long unsigned int call_site, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr, size_t bytes_alloc, gfp_t gfp_flags);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    long unsigned int call_site;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    size_t bytes_alloc;
    long unsigned int gfp_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, long unsigned int call_site, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr, size_t bytes_alloc, gfp_t gfp_flags);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    long unsigned int call_site;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    size_t bytes_alloc;
    long unsigned int gfp_flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, long unsigned int call_site, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr, size_t bytes_alloc, gfp_t gfp_flags);
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
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
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
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_percpu_alloc_percpu {
    struct trace_entry ent;
    bool reserved;
    bool is_atomic;
    size_t size;
    size_t align;
    void *base_addr;
    int off;
    void *ptr;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_percpu_alloc_percpu(void *__data, bool reserved, bool is_atomic, size_t size, size_t align, void *base_addr, int off, void *ptr);
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Field added. </b>
<code>long unsigned int call_site</code>
</li>
<li>
<b>Field added. </b>
<code>size_t bytes_alloc</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int gfp_flags</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int call_site</code>
</li>
<li>
<b>Param added. </b>
<code>size_t bytes_alloc</code>
</li>
<li>
<b>Param added. </b>
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, reserved, is_atomic, size, align, base_addr, off, ptr</code> ➡️ <code>__data, call_site, reserved, is_atomic, size, align, base_addr, off, ptr, bytes_alloc, gfp_flags</code>
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
