# Tracepoint: <code>hugepage_set_pmd</code>

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
struct trace_event_raw_hugepage_set_pmd {
    struct trace_entry ent;
    long unsigned int addr;
    long unsigned int pmd;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_hugepage_set_pmd(void *__data, long unsigned int addr, long unsigned int pmd);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_hugepage_set_pmd {
    struct trace_entry ent;
    long unsigned int addr;
    long unsigned int pmd;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_hugepage_set_pmd(void *__data, long unsigned int addr, long unsigned int pmd);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_hugepage_set_pmd {
    struct trace_entry ent;
    long unsigned int addr;
    long unsigned int pmd;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_hugepage_set_pmd(void *__data, long unsigned int addr, long unsigned int pmd);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_hugepage_set {
    struct trace_entry ent;
    long unsigned int addr;
    long unsigned int pte;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_hugepage_set(void *__data, long unsigned int addr, long unsigned int pte);
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_hugepage_set_pmd {
    struct trace_entry ent;
    long unsigned int addr;
    long unsigned int pmd;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_hugepage_set_pmd(void *__data, long unsigned int addr, long unsigned int pmd);
```
</details>
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
<b>Field added. </b>
<code>long unsigned int pte</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int pmd</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int pte</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int pmd</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
