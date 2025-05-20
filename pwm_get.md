# Tracepoint: <code>pwm_get</code>

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
struct trace_event_raw_pwm {
    struct trace_entry ent;
    struct pwm_device *pwm;
    u64 period;
    u64 duty_cycle;
    enum pwm_polarity polarity;
    bool enabled;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_pwm {
    struct trace_entry ent;
    struct pwm_device *pwm;
    u64 period;
    u64 duty_cycle;
    enum pwm_polarity polarity;
    bool enabled;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_pwm {
    struct trace_entry ent;
    struct pwm_device *pwm;
    u64 period;
    u64 duty_cycle;
    enum pwm_polarity polarity;
    bool enabled;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_pwm {
    struct trace_entry ent;
    struct pwm_device *pwm;
    u64 period;
    u64 duty_cycle;
    enum pwm_polarity polarity;
    bool enabled;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_pwm {
    struct trace_entry ent;
    struct pwm_device *pwm;
    u64 period;
    u64 duty_cycle;
    enum pwm_polarity polarity;
    bool enabled;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_pwm {
    struct trace_entry ent;
    struct pwm_device *pwm;
    u64 period;
    u64 duty_cycle;
    enum pwm_polarity polarity;
    bool enabled;
    int err;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_pwm {
    struct trace_entry ent;
    struct pwm_device *pwm;
    u64 period;
    u64 duty_cycle;
    enum pwm_polarity polarity;
    bool enabled;
    int err;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_pwm {
    struct trace_entry ent;
    struct pwm_device *pwm;
    u64 period;
    u64 duty_cycle;
    enum pwm_polarity polarity;
    bool enabled;
    int err;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
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
<b>Field added. </b>
<code>int err</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>int err</code>
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
