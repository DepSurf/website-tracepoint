# Tracepoint: <code>cros_ec_request_done</code>

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
struct trace_event_raw_cros_ec_request_done {
    struct trace_entry ent;
    uint32_t version;
    uint32_t command;
    uint32_t result;
    int retval;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_request_done(void *__data, struct cros_ec_command *cmd, int retval);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_cros_ec_request_done {
    struct trace_entry ent;
    uint32_t version;
    uint32_t offset;
    uint32_t command;
    uint32_t outsize;
    uint32_t insize;
    uint32_t result;
    int retval;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_request_done(void *__data, struct cros_ec_command *cmd, int retval);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_cros_ec_request_done {
    struct trace_entry ent;
    uint32_t version;
    uint32_t offset;
    uint32_t command;
    uint32_t outsize;
    uint32_t insize;
    uint32_t result;
    int retval;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_request_done(void *__data, struct cros_ec_command *cmd, int retval);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_cros_ec_request_done {
    struct trace_entry ent;
    uint32_t version;
    uint32_t offset;
    uint32_t command;
    uint32_t outsize;
    uint32_t insize;
    uint32_t result;
    int retval;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_request_done(void *__data, struct cros_ec_command *cmd, int retval);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_cros_ec_request_done {
    struct trace_entry ent;
    uint32_t version;
    uint32_t offset;
    uint32_t command;
    uint32_t outsize;
    uint32_t insize;
    uint32_t result;
    int retval;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_request_done(void *__data, struct cros_ec_command *cmd, int retval);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_cros_ec_request_done {
    struct trace_entry ent;
    uint32_t version;
    uint32_t offset;
    uint32_t command;
    uint32_t outsize;
    uint32_t insize;
    uint32_t result;
    int retval;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_request_done(void *__data, struct cros_ec_command *cmd, int retval);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_cros_ec_request_done {
    struct trace_entry ent;
    uint32_t version;
    uint32_t offset;
    uint32_t command;
    uint32_t outsize;
    uint32_t insize;
    uint32_t result;
    int retval;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_request_done(void *__data, struct cros_ec_command *cmd, int retval);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_cros_ec_request_done {
    struct trace_entry ent;
    uint32_t version;
    uint32_t offset;
    uint32_t command;
    uint32_t outsize;
    uint32_t insize;
    uint32_t result;
    int retval;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_request_done(void *__data, struct cros_ec_command *cmd, int retval);
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
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field added. </b>
<code>uint32_t offset</code>
</li>
<li>
<b>Field added. </b>
<code>uint32_t outsize</code>
</li>
<li>
<b>Field added. </b>
<code>uint32_t insize</code>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
