# Tracepoint: <code>block_sleeprq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
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
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
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
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_block_get_rq {
    struct trace_entry ent;
    dev_t dev;
    sector_t sector;
    unsigned int nr_sector;
    char rwbs[8];
    char comm[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_block_get_rq(void *__data, struct request_queue *q, struct bio *bio, int rw);
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
