# Tracepoint: <code>xhci_free_virt_device</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    int devnum;
    int state;
    int speed;
    u8 portnum;
    u8 level;
    int slot_id;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    int devnum;
    int state;
    int speed;
    u8 portnum;
    u8 level;
    int slot_id;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
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
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
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
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_xhci_log_free_virt_dev {
    struct trace_entry ent;
    void *vdev;
    long long unsigned int out_ctx;
    long long unsigned int in_ctx;
    u8 fake_port;
    u8 real_port;
    u16 current_mel;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_xhci_log_free_virt_dev(void *__data, struct xhci_virt_device *vdev);
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field added. </b>
<code>u8 fake_port</code>
</li>
<li>
<b>Field added. </b>
<code>u8 real_port</code>
</li>
<li>
<b>Field added. </b>
<code>u16 current_mel</code>
</li>
<li>
<b>Field removed. </b>
<code>int devnum</code>
</li>
<li>
<b>Field removed. </b>
<code>int state</code>
</li>
<li>
<b>Field removed. </b>
<code>int speed</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 portnum</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 level</code>
</li>
<li>
<b>Field removed. </b>
<code>int slot_id</code>
</li>
</ul>
</details>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
