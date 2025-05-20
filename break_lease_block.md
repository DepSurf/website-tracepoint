# Tracepoint: <code>break_lease_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_next;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_next;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_next;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_next;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_next;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_next;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
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
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
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
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

Event:

```c
struct trace_event_raw_filelock_lease {
    struct trace_entry ent;
    struct file_lock *fl;
    long unsigned int i_ino;
    dev_t s_dev;
    struct file_lock *fl_blocker;
    fl_owner_t fl_owner;
    unsigned int fl_flags;
    unsigned char fl_type;
    long unsigned int fl_break_time;
    long unsigned int fl_downgrade_time;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_filelock_lease(void *__data, struct inode *inode, struct file_lock *fl);
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
<code>struct file_lock *fl_blocker</code>
</li>
<li>
<b>Field removed. </b>
<code>struct file_lock *fl_next</code>
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
