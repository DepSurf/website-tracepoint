# Tracepoint: <code>ata_qc_prep</code>

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
struct trace_event_raw_ata_qc_issue_template {
    struct trace_entry ent;
    unsigned int ata_port;
    unsigned int ata_dev;
    unsigned int tag;
    unsigned char cmd;
    unsigned char dev;
    unsigned char lbal;
    unsigned char lbam;
    unsigned char lbah;
    unsigned char nsect;
    unsigned char feature;
    unsigned char hob_lbal;
    unsigned char hob_lbam;
    unsigned char hob_lbah;
    unsigned char hob_nsect;
    unsigned char hob_feature;
    unsigned char ctl;
    unsigned char proto;
    long unsigned int flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ata_qc_issue_template(void *__data, struct ata_queued_cmd *qc);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ata_qc_issue_template {
    struct trace_entry ent;
    unsigned int ata_port;
    unsigned int ata_dev;
    unsigned int tag;
    unsigned char cmd;
    unsigned char dev;
    unsigned char lbal;
    unsigned char lbam;
    unsigned char lbah;
    unsigned char nsect;
    unsigned char feature;
    unsigned char hob_lbal;
    unsigned char hob_lbam;
    unsigned char hob_lbah;
    unsigned char hob_nsect;
    unsigned char hob_feature;
    unsigned char ctl;
    unsigned char proto;
    long unsigned int flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ata_qc_issue_template(void *__data, struct ata_queued_cmd *qc);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ata_qc_issue_template {
    struct trace_entry ent;
    unsigned int ata_port;
    unsigned int ata_dev;
    unsigned int tag;
    unsigned char cmd;
    unsigned char dev;
    unsigned char lbal;
    unsigned char lbam;
    unsigned char lbah;
    unsigned char nsect;
    unsigned char feature;
    unsigned char hob_lbal;
    unsigned char hob_lbam;
    unsigned char hob_lbah;
    unsigned char hob_nsect;
    unsigned char hob_feature;
    unsigned char ctl;
    unsigned char proto;
    long unsigned int flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ata_qc_issue_template(void *__data, struct ata_queued_cmd *qc);
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

Event:

```c
struct trace_event_raw_ata_qc_issue_template {
    struct trace_entry ent;
    unsigned int ata_port;
    unsigned int ata_dev;
    unsigned int tag;
    unsigned char cmd;
    unsigned char dev;
    unsigned char lbal;
    unsigned char lbam;
    unsigned char lbah;
    unsigned char nsect;
    unsigned char feature;
    unsigned char hob_lbal;
    unsigned char hob_lbam;
    unsigned char hob_lbah;
    unsigned char hob_nsect;
    unsigned char hob_feature;
    unsigned char ctl;
    unsigned char proto;
    long unsigned int flags;
    char __data[0];
};
```
Function:

```c
void trace_event_raw_event_ata_qc_issue_template(void *__data, struct ata_queued_cmd *qc);
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
