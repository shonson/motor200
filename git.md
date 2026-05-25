# Demo200 项目

**远程仓库：** https://github.com/shonson/motor200.git

---

## 上传操作汇总

### 执行的有效指令

| 步骤 | 命令 | 说明 |
|------|------|------|
| 1 | `git status` | 检查当前 Git 状态，确认仓库已初始化 |
| 2 | `git remote -v` | 确认远程仓库 origin 已配置为 motor200.git |
| 3 | `git add -A` | 将所有文件（21个）添加到暂存区 |
| 4 | `git commit -m "Initial commit: Demo200 project files"` | 提交更改，创建 root-commit `ac1361d` |
| 5 | `git push -u origin main` | 推送到远程仓库 main 分支 |

### 上传的文件清单（共21个）

| 文件路径 | 说明 |
|----------|------|
| `common/common.tcl` | 公共 Tcl 脚本 |
| `script.tcl` | 主脚本 |
| `git.md` | 本文件 |
| `SK1ABLEN_2024/component/work/MC_System_sb_MSS/MC_System_sb_MSS.v` | MSS 模块 Verilog 文件 |
| `SK1ABLEN_2024/component/work/MC_System_sb_MSS/MC_System_sb_MSS_syn.v` | MSS 模块综合文件 |
| `src/1_create_design.tcl` | 创建设计脚本 |
| `src/2_constrain_design.tcl` | 约束设计脚本 |
| `src/4_implement_design.tcl` | 实现设计脚本 |
| `src/5_program_design.tcl` | 编程设计脚本 |
| `src/components/BLDC_Encoder_Axis.tcl` | BLDC 编码器轴组件 |
| `src/components/MC_System.tcl` | 电机控制系统组件 |
| `src/components/MC_System_sb.tcl` | 电机控制子系统组件 |
| `src/components/apb3_en_if.tcl` | APB3 使能接口组件 |
| `src/components/top.tcl` | 顶层组件 |
| `src/constraints/io_constraints.pdc` | IO 约束文件 |
| `src/constraints/timing_user_constraints.sdc` | 时序约束文件 |
| `src/cxf/MC_System_sb_MSS.cxf` | MSS 配置文件 |
| `src/cxf/MC_System_sb_MSS.sdb` | MSS 系统数据库 |
| `src/hdl/adc_interface_795x.vhd` | ADC 接口 VHDL 文件 |
| `src/hdl/apb3_en_if.vhd` | APB3 使能接口 VHDL 文件 |
| `src/softconsole/MotorControl_5_1.hex` | 电机控制固件 HEX 文件 |

### 当前状态

- **分支：** main
- **最新提交：** `ac1361d` - "Initial commit: Demo200 project files"
- **远程同步：** origin/main 已同步
