# Tracepoint: <code>extlog_mem_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    uuid_le fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const uuid_le *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    uuid_le fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const uuid_le *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    uuid_le fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const uuid_le *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    uuid_le fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const uuid_le *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    uuid_le fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const uuid_le *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    uuid_le fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const uuid_le *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    uuid_le fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const uuid_le *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    guid_t fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const guid_t *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    guid_t fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const guid_t *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    guid_t fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const guid_t *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    guid_t fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const guid_t *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    guid_t fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const guid_t *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    guid_t fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const guid_t *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    guid_t fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const guid_t *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    guid_t fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const guid_t *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    guid_t fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const guid_t *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    guid_t fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const guid_t *fru_id, const char *fru_text, u8 sev);
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
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    guid_t fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const guid_t *fru_id, const char *fru_text, u8 sev);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_extlog_mem_event {
    struct trace_entry ent;
    u32 err_seq;
    u8 etype;
    u8 sev;
    u64 pa;
    u8 pa_mask_lsb;
    guid_t fru_id;
    u32 __data_loc_fru_text;
    struct cper_mem_err_compact data;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_extlog_mem_event(void *__data, struct cper_sec_mem_err *mem, u32 err_seq, const guid_t *fru_id, const char *fru_text, u8 sev);
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field type changed. </b>
<code>uuid_le fru_id</code> ➡️ <code>guid_t fru_id</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param type changed. </b>
<code>const uuid_le *fru_id</code> ➡️ <code>const guid_t *fru_id</code>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
