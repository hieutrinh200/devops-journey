# Day 03 - Permissions, ownership & processes

## Key terms (EN/VI)
- Permission bits (r/w/x): Read, Write, Execute for user/group/others  
  → Quyền r/w/x cho owner/nhóm/người khác.
- Symbolic vs Octal mode: `u+x`, `g-r` vs `750`  
  → Hai cách ghi quyền: ký hiệu và số.
- Owner/Group: File has an owner user and a primary group  
  → File có chủ sở hữu và nhóm chính.
- Process & PID: A running program instance with a Process ID  
  → Tiến trình & PID: chương trình đang chạy có mã định danh.
- Signals (SIGTERM/SIGKILL): Graceful stop vs force kill  
  → Tín hiệu dừng: nhẹ nhàng vs cưỡng bức.

## Commands practiced
chmod (u/g/o, +/-, r/w/x), chmod 750, chown, chgrp, ps aux, pgrep, kill -15/-9, top
Bandit: ls -la, file, strings, find (size/readable), cat với tên file “đặc biệt”.

