# Tracepoint: <code>x86_fpu_before_restore</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool load_fpu;
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
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool load_fpu;
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
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool load_fpu;
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
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool load_fpu;
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
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool load_fpu;
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
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool load_fpu;
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
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool load_fpu;
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
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool load_fpu;
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
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool load_fpu;
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
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool load_fpu;
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
<details>
<summary>In <code>aws</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool load_fpu;
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
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool load_fpu;
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
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool load_fpu;
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
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_x86_fpu {
    struct trace_entry ent;
    struct fpu *fpu;
    bool load_fpu;
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
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field added. </b>
<code>bool load_fpu</code>
</li>
<li>
<b>Field removed. </b>
<code>bool initialized</code>
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
