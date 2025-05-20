# Tracepoint: <code>ext4_remove_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    long long int partial;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, long long int partial_cluster);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    long long int partial;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, long long int partial_cluster);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    long long int partial;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, long long int partial_cluster);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    long long int partial;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, long long int partial_cluster);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    long long int partial;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, long long int partial_cluster);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    long long int partial;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, long long int partial_cluster);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
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
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
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
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ext4_remove_blocks {
    struct trace_entry ent;
    dev_t dev;
    ino_t ino;
    ext4_lblk_t from;
    ext4_lblk_t to;
    ext4_fsblk_t ee_pblk;
    ext4_lblk_t ee_lblk;
    short unsigned int ee_len;
    ext4_fsblk_t pc_pclu;
    ext4_lblk_t pc_lblk;
    int pc_state;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ext4_remove_blocks(void *__data, struct inode *inode, struct ext4_extent *ex, ext4_lblk_t from, ext4_fsblk_t to, struct partial_cluster *pc);
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Event changed. </b>
</li>
<li>
<b>Field added. </b>
<code>ext4_fsblk_t pc_pclu</code>
</li>
<li>
<b>Field added. </b>
<code>ext4_lblk_t pc_lblk</code>
</li>
<li>
<b>Field added. </b>
<code>int pc_state</code>
</li>
<li>
<b>Field removed. </b>
<code>long long int partial</code>
</li>
<li>
<b>Func changed. </b>
</li>
<li>
<b>Param added. </b>
<code>struct partial_cluster *pc</code>
</li>
<li>
<b>Param removed. </b>
<code>long long int partial_cluster</code>
</li>
</ul>
</details>
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
