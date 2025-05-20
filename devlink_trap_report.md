# Tracepoint: <code>devlink_trap_report</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_devlink_trap_report {
    struct trace_entry ent;
    u32 __data_loc_bus_name;
    u32 __data_loc_dev_name;
    u32 __data_loc_driver_name;
    u32 __data_loc_trap_name;
    u32 __data_loc_trap_group_name;
    u32 __data_loc_input_dev_name;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_devlink_trap_report(void *__data, const struct devlink *devlink, struct sk_buff *skb, const struct devlink_trap_metadata *metadata);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_devlink_trap_report {
    struct trace_entry ent;
    u32 __data_loc_bus_name;
    u32 __data_loc_dev_name;
    u32 __data_loc_driver_name;
    u32 __data_loc_trap_name;
    u32 __data_loc_trap_group_name;
    u32 __data_loc_input_dev_name;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_devlink_trap_report(void *__data, const struct devlink *devlink, struct sk_buff *skb, const struct devlink_trap_metadata *metadata);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_devlink_trap_report {
    struct trace_entry ent;
    u32 __data_loc_bus_name;
    u32 __data_loc_dev_name;
    u32 __data_loc_driver_name;
    u32 __data_loc_trap_name;
    u32 __data_loc_trap_group_name;
    u32 __data_loc_input_dev_name;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_devlink_trap_report(void *__data, const struct devlink *devlink, struct sk_buff *skb, const struct devlink_trap_metadata *metadata);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_devlink_trap_report {
    struct trace_entry ent;
    u32 __data_loc_bus_name;
    u32 __data_loc_dev_name;
    u32 __data_loc_driver_name;
    u32 __data_loc_trap_name;
    u32 __data_loc_trap_group_name;
    u32 __data_loc_input_dev_name;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_devlink_trap_report(void *__data, const struct devlink *devlink, struct sk_buff *skb, const struct devlink_trap_metadata *metadata);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_devlink_trap_report {
    struct trace_entry ent;
    u32 __data_loc_bus_name;
    u32 __data_loc_dev_name;
    u32 __data_loc_driver_name;
    u32 __data_loc_trap_name;
    u32 __data_loc_trap_group_name;
    char input_dev_name[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_devlink_trap_report(void *__data, const struct devlink *devlink, struct sk_buff *skb, const struct devlink_trap_metadata *metadata);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_devlink_trap_report {
    struct trace_entry ent;
    u32 __data_loc_bus_name;
    u32 __data_loc_dev_name;
    u32 __data_loc_driver_name;
    u32 __data_loc_trap_name;
    u32 __data_loc_trap_group_name;
    char input_dev_name[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_devlink_trap_report(void *__data, const struct devlink *devlink, struct sk_buff *skb, const struct devlink_trap_metadata *metadata);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_devlink_trap_report {
    struct trace_entry ent;
    u32 __data_loc_bus_name;
    u32 __data_loc_dev_name;
    u32 __data_loc_driver_name;
    u32 __data_loc_trap_name;
    u32 __data_loc_trap_group_name;
    char input_dev_name[16];
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_devlink_trap_report(void *__data, const struct devlink *devlink, struct sk_buff *skb, const struct devlink_trap_metadata *metadata);
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
<b>Field added. </b>
<code>char input_dev_name[16]</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 __data_loc_input_dev_name</code>
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
