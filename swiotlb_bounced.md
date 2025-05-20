# Tracepoint: <code>swiotlb_bounced</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    int swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, int swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    int swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, int swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    bool force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    bool force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    bool force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    bool force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
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
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
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
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_swiotlb_bounced {
    struct trace_entry ent;
    u32 __data_loc_dev_name;
    u64 dma_mask;
    dma_addr_t dev_addr;
    size_t size;
    enum swiotlb_force swiotlb_force;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field type changed. </b>
<code>int swiotlb_force</code> ➡️ <code>enum swiotlb_force swiotlb_force</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param type changed. </b>
<code>int swiotlb_force</code> ➡️ <code>enum swiotlb_force swiotlb_force</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field added. </b>
<code>bool force</code>
</li>
<li>
<b>Field removed. </b>
<code>enum swiotlb_force swiotlb_force</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param removed. </b>
<code>enum swiotlb_force swiotlb_force</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
