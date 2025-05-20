# Tracepoint: <code>ext4_prefetch_bitmaps</code>

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
struct trace_event_raw_ext4_prefetch_bitmaps {
    struct trace_entry ent;
    dev_t dev;
    __u32 group;
    __u32 next;
    __u32 ios;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_prefetch_bitmaps(void *__data, struct super_block *sb, ext4_group_t group, ext4_group_t next, unsigned int prefetch_ios);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_prefetch_bitmaps {
    struct trace_entry ent;
    dev_t dev;
    __u32 group;
    __u32 next;
    __u32 ios;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_prefetch_bitmaps(void *__data, struct super_block *sb, ext4_group_t group, ext4_group_t next, unsigned int prefetch_ios);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_prefetch_bitmaps {
    struct trace_entry ent;
    dev_t dev;
    __u32 group;
    __u32 next;
    __u32 ios;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_prefetch_bitmaps(void *__data, struct super_block *sb, ext4_group_t group, ext4_group_t next, unsigned int prefetch_ios);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_prefetch_bitmaps {
    struct trace_entry ent;
    dev_t dev;
    __u32 group;
    __u32 next;
    __u32 ios;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_prefetch_bitmaps(void *__data, struct super_block *sb, ext4_group_t group, ext4_group_t next, unsigned int prefetch_ios);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_prefetch_bitmaps {
    struct trace_entry ent;
    dev_t dev;
    __u32 group;
    __u32 next;
    __u32 ios;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_prefetch_bitmaps(void *__data, struct super_block *sb, ext4_group_t group, ext4_group_t next, unsigned int prefetch_ios);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_prefetch_bitmaps {
    struct trace_entry ent;
    dev_t dev;
    __u32 group;
    __u32 next;
    __u32 ios;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_prefetch_bitmaps(void *__data, struct super_block *sb, ext4_group_t group, ext4_group_t next, unsigned int prefetch_ios);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_prefetch_bitmaps {
    struct trace_entry ent;
    dev_t dev;
    __u32 group;
    __u32 next;
    __u32 ios;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_prefetch_bitmaps(void *__data, struct super_block *sb, ext4_group_t group, ext4_group_t next, unsigned int prefetch_ios);
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
