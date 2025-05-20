# Tracepoint: <code>x86_fpu_activate_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool fpregs_active;
    bool fpstate_active;
    int counter;
    u64 xfeatures;
    u64 xcomp_bv;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_x86_fpu(void *__data, struct fpu *fpu);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool fpregs_active;
    bool fpstate_active;
    u64 xfeatures;
    u64 xcomp_bv;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_x86_fpu(void *__data, struct fpu *fpu);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool fpregs_active;
    bool fpstate_active;
    u64 xfeatures;
    u64 xcomp_bv;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_x86_fpu(void *__data, struct fpu *fpu);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool initialized;
    u64 xfeatures;
    u64 xcomp_bv;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_x86_fpu(void *__data, struct fpu *fpu);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool initialized;
    u64 xfeatures;
    u64 xcomp_bv;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_x86_fpu(void *__data, struct fpu *fpu);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool initialized;
    u64 xfeatures;
    u64 xcomp_bv;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_x86_fpu(void *__data, struct fpu *fpu);
```
</details>
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
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field removed. </b>
<code>int counter</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field added. </b>
<code>bool initialized</code>
</li>
<li>
<b>Field removed. </b>
<code>bool fpregs_active</code>
</li>
<li>
<b>Field removed. </b>
<code>bool fpstate_active</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
