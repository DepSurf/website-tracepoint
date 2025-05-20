# Tracepoint: <code>bounce_unmap_single</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_dma_unmap {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    dma_addr_t dev_addr;
    size_t size;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_dma_unmap(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_dma_unmap {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    dma_addr_t dev_addr;
    size_t size;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_dma_unmap(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_dma_unmap {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    dma_addr_t dev_addr;
    size_t size;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_dma_unmap(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

Event:

```c
struct trace_event_raw_dma_unmap {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    dma_addr_t dev_addr;
    size_t size;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_dma_unmap(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_dma_unmap {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    dma_addr_t dev_addr;
    size_t size;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_dma_unmap(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_dma_unmap {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    dma_addr_t dev_addr;
    size_t size;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_dma_unmap(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_dma_unmap {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    dma_addr_t dev_addr;
    size_t size;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_dma_unmap(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
