# Tracepoint: <code>jbd2_handle_restart</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_jbd2_handle_start_class {
    struct trace_entry ent;
    dev_t dev;
    long unsigned int tid;
    unsigned int type;
    unsigned int line_no;
    int requested_blocks;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_jbd2_handle_start_class(void *__data, dev_t dev, long unsigned int tid, unsigned int type, unsigned int line_no, int requested_blocks);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_jbd2_handle_start_class {
    struct trace_entry ent;
    dev_t dev;
    long unsigned int tid;
    unsigned int type;
    unsigned int line_no;
    int requested_blocks;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_jbd2_handle_start_class(void *__data, dev_t dev, long unsigned int tid, unsigned int type, unsigned int line_no, int requested_blocks);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_jbd2_handle_start_class {
    struct trace_entry ent;
    dev_t dev;
    long unsigned int tid;
    unsigned int type;
    unsigned int line_no;
    int requested_blocks;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_jbd2_handle_start_class(void *__data, dev_t dev, long unsigned int tid, unsigned int type, unsigned int line_no, int requested_blocks);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_jbd2_handle_start_class {
    struct trace_entry ent;
    dev_t dev;
    long unsigned int tid;
    unsigned int type;
    unsigned int line_no;
    int requested_blocks;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_jbd2_handle_start_class(void *__data, dev_t dev, long unsigned int tid, unsigned int type, unsigned int line_no, int requested_blocks);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_jbd2_handle_start_class {
    struct trace_entry ent;
    dev_t dev;
    long unsigned int tid;
    unsigned int type;
    unsigned int line_no;
    int requested_blocks;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_jbd2_handle_start_class(void *__data, dev_t dev, long unsigned int tid, unsigned int type, unsigned int line_no, int requested_blocks);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_jbd2_handle_start_class {
    struct trace_entry ent;
    dev_t dev;
    tid_t tid;
    unsigned int type;
    unsigned int line_no;
    int requested_blocks;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_jbd2_handle_start_class(void *__data, dev_t dev, tid_t tid, unsigned int type, unsigned int line_no, int requested_blocks);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_jbd2_handle_start_class {
    struct trace_entry ent;
    dev_t dev;
    tid_t tid;
    unsigned int type;
    unsigned int line_no;
    int requested_blocks;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_jbd2_handle_start_class(void *__data, dev_t dev, tid_t tid, unsigned int type, unsigned int line_no, int requested_blocks);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_jbd2_handle_start_class {
    struct trace_entry ent;
    dev_t dev;
    tid_t tid;
    unsigned int type;
    unsigned int line_no;
    int requested_blocks;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_jbd2_handle_start_class(void *__data, dev_t dev, tid_t tid, unsigned int type, unsigned int line_no, int requested_blocks);
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int tid</code> ➡️ <code>tid_t tid</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int tid</code> ➡️ <code>tid_t tid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
