normal:   No attack
attack1:  Malicious command injection(Manipulated Variable:Production Setpoint)
attack2:  Malicious command injection(Manipulated Variable:Stripper Level Setpoint)
attack3:  Malicious command injection(Manipulated Variables:yA Setpoint、yAC Setpoint)
attack4:  Physical process disturbance(Manipulated Variable:A and C feed ratio)
attack5:  Physical process disturbance(Manipulated Variable:Cooling water outlet valve of reactor)
attack6:  Physical process disturbance(Manipulated Variable:Cooling water outlet valve of separator)
attack7:  False data injection(Manipulated Variable:Stripper level)
attack8:  Dos(Manipulated Variable:PLC for controlling the separator unit)

In the file normal.csv, the data are all under normal working conditions, and their labels are 0.

In the file attack1~8.csv, the data label when it is not attacked is 0, and the label after it is attacked is not 0, which is 1-8, corresponding to different attack conditions respectively.