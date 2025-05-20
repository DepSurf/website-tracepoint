# Tracepoint: <code>cros_ec_cmd</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_cros_ec_cmd_class {
    struct trace_entry ent;
    uint32_t version;
    uint32_t command;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_cmd_class(void *__data, struct cros_ec_command *cmd);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_cros_ec_cmd_class {
    struct trace_entry ent;
    uint32_t version;
    uint32_t command;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_cmd_class(void *__data, struct cros_ec_command *cmd);
```
</details>
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
struct trace_event_raw_cros_ec_cmd_class {
    struct trace_entry ent;
    uint32_t version;
    uint32_t command;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_cmd_class(void *__data, struct cros_ec_command *cmd);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_cros_ec_cmd_class {
    struct trace_entry ent;
    uint32_t version;
    uint32_t command;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_cmd_class(void *__data, struct cros_ec_command *cmd);
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

Event:

```c
struct trace_event_raw_cros_ec_cmd_class {
    struct trace_entry ent;
    uint32_t version;
    uint32_t command;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_cmd_class(void *__data, struct cros_ec_command *cmd);
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_cros_ec_cmd_class {
    struct trace_entry ent;
    uint32_t version;
    uint32_t command;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_cmd_class(void *__data, struct cros_ec_command *cmd);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_cros_ec_cmd_class {
    struct trace_entry ent;
    uint32_t version;
    uint32_t command;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_cros_ec_cmd_class(void *__data, struct cros_ec_command *cmd);
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
