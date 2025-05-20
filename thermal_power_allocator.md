# Tracepoint: <code>thermal_power_allocator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 total_req_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 total_req_power, u32 total_granted_power, int num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
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
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
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
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_thermal_power_allocator {
    struct trace_entry ent;
    int tz_id;
    u32 __data_loc_req_power;
    u32 total_req_power;
    u32 __data_loc_granted_power;
    u32 total_granted_power;
    size_t num_actors;
    u32 power_range;
    u32 max_allocatable_power;
    int current_temp;
    s32 delta_temp;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field removed. </b>
<code>u32 __data_loc_req_power</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 __data_loc_granted_power</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param removed. </b>
<code>u32 *req_power</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *granted_power</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, tz, req_power, total_req_power, granted_power, total_granted_power, num_actors, power_range, max_allocatable_power, current_temp, delta_temp</code> ➡️ <code>__data, tz, total_req_power, total_granted_power, num_actors, power_range, max_allocatable_power, current_temp, delta_temp</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t num_actors</code> ➡️ <code>int num_actors</code>
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
