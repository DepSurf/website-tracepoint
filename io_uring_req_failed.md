# Tracepoint: <code>io_uring_req_failed</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_io_uring_req_failed {
    struct trace_entry ent;
    void *ctx;
    void *req;
    long long unsigned int user_data;
    u8 opcode;
    u8 flags;
    u8 ioprio;
    u64 off;
    u64 addr;
    u32 len;
    u32 op_flags;
    u16 buf_index;
    u16 personality;
    u32 file_index;
    u64 pad1;
    u64 addr3;
    int error;
    u32 __data_loc_op_str;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_io_uring_req_failed(void *__data, const struct io_uring_sqe *sqe, void *ctx, void *req, int error);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_io_uring_req_failed {
    struct trace_entry ent;
    void *ctx;
    void *req;
    long long unsigned int user_data;
    u8 opcode;
    u8 flags;
    u8 ioprio;
    u64 off;
    u64 addr;
    u32 len;
    u32 op_flags;
    u16 buf_index;
    u16 personality;
    u32 file_index;
    u64 pad1;
    u64 addr3;
    int error;
    u32 __data_loc_op_str;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_io_uring_req_failed(void *__data, const struct io_uring_sqe *sqe, struct io_kiocb *req, int error);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_io_uring_req_failed {
    struct trace_entry ent;
    void *ctx;
    void *req;
    long long unsigned int user_data;
    u8 opcode;
    u8 flags;
    u8 ioprio;
    u64 off;
    u64 addr;
    u32 len;
    u32 op_flags;
    u16 buf_index;
    u16 personality;
    u32 file_index;
    u64 pad1;
    u64 addr3;
    int error;
    u32 __data_loc_op_str;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_io_uring_req_failed(void *__data, const struct io_uring_sqe *sqe, struct io_kiocb *req, int error);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_io_uring_req_failed {
    struct trace_entry ent;
    void *ctx;
    void *req;
    long long unsigned int user_data;
    u8 opcode;
    u8 flags;
    u8 ioprio;
    u64 off;
    u64 addr;
    u32 len;
    u32 op_flags;
    u16 buf_index;
    u16 personality;
    u32 file_index;
    u64 pad1;
    u64 addr3;
    int error;
    u32 __data_loc_op_str;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_io_uring_req_failed(void *__data, const struct io_uring_sqe *sqe, struct io_kiocb *req, int error);
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param removed. </b>
<code>void *ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, sqe, ctx, req, error</code> ➡️ <code>__data, sqe, req, error</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *req</code> ➡️ <code>struct io_kiocb *req</code>
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
