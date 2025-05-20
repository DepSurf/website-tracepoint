# Tracepoint: <code>io_uring_submit_sqe</code>

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
struct trace_event_raw_io_uring_submit_sqe {
    struct trace_entry ent;
    void *ctx;
    u8 opcode;
    u64 user_data;
    bool force_nonblock;
    bool sq_thread;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_io_uring_submit_sqe(void *__data, void *ctx, u8 opcode, u64 user_data, bool force_nonblock, bool sq_thread);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_io_uring_submit_sqe {
    struct trace_entry ent;
    void *ctx;
    u8 opcode;
    u64 user_data;
    bool force_nonblock;
    bool sq_thread;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_io_uring_submit_sqe(void *__data, void *ctx, u8 opcode, u64 user_data, bool force_nonblock, bool sq_thread);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_io_uring_submit_sqe {
    struct trace_entry ent;
    void *ctx;
    u8 opcode;
    u64 user_data;
    bool force_nonblock;
    bool sq_thread;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_io_uring_submit_sqe(void *__data, void *ctx, u8 opcode, u64 user_data, bool force_nonblock, bool sq_thread);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_io_uring_submit_sqe {
    struct trace_entry ent;
    void *ctx;
    void *req;
    u8 opcode;
    u64 user_data;
    u32 flags;
    bool force_nonblock;
    bool sq_thread;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_io_uring_submit_sqe(void *__data, void *ctx, void *req, u8 opcode, u64 user_data, u32 flags, bool force_nonblock, bool sq_thread);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_io_uring_submit_sqe {
    struct trace_entry ent;
    void *ctx;
    void *req;
    long long unsigned int user_data;
    u8 opcode;
    u32 flags;
    bool force_nonblock;
    bool sq_thread;
    u32 __data_loc_op_str;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_io_uring_submit_sqe(void *__data, void *ctx, void *req, long long unsigned int user_data, u8 opcode, u32 flags, bool force_nonblock, bool sq_thread);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_io_uring_submit_sqe {
    struct trace_entry ent;
    void *ctx;
    void *req;
    long long unsigned int user_data;
    u8 opcode;
    u32 flags;
    bool force_nonblock;
    bool sq_thread;
    u32 __data_loc_op_str;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_io_uring_submit_sqe(void *__data, struct io_kiocb *req, bool force_nonblock);
```
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field added. </b>
<code>void *req</code>
</li>
<li>
<b>Field added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>void *req</code>
</li>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, opcode, user_data, force_nonblock, sq_thread</code> ➡️ <code>__data, ctx, req, opcode, user_data, flags, force_nonblock, sq_thread</code>
</li>
</ul>
</details>
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
<code>u32 __data_loc_op_str</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 user_data</code> ➡️ <code>long long unsigned int user_data</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, req, opcode, user_data, flags, force_nonblock, sq_thread</code> ➡️ <code>__data, ctx, req, user_data, opcode, flags, force_nonblock, sq_thread</code>
</li>
<li>
<b>Param type changed. </b>
<code>u64 user_data</code> ➡️ <code>long long unsigned int user_data</code>
</li>
</ul>
</details>
</li>
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
<b>Param removed. </b>
<code>long long unsigned int user_data</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 opcode</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool sq_thread</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, req, user_data, opcode, flags, force_nonblock, sq_thread</code> ➡️ <code>__data, req, force_nonblock</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *req</code> ➡️ <code>struct io_kiocb *req</code>
</li>
</ul>
</details>
</li>
</ul>
