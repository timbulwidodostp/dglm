# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Double generalized linear models Use dglm With (In) R Software
install.packages("dglm")
library("dglm")
dglm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/dglm/main/dglm/dglm.csv",sep = ";")
# Estimation A function to calculate the concentration index Statistical Analysis of Health Inequalities Use rineq (ci) With (In) R Software
dglm <- dglm(lot1 ~ log(u), ~1, data = dglm, family = Gamma)
summary(dglm)
# Double generalized linear models Use dglm With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished