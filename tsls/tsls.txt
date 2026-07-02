# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Two-Stage Least Squares (TSLS) Use tsls (sem) With (In) R Software
install.packages("sem")
library("sem")
# Estimation Two-Stage Least Squares (TSLS) Use tsls (sem) With (In) R Software
tsls = read.csv("https://raw.githubusercontent.com/timbulwidodostp/tsls/main/tsls/tsls.csv",sep = ";")
tsls <- tsls(tsls ~ tsls_1 + tsls_2, ~ tsls_1 + tsls_3 + tsls_4, data = tsls)
summary(tsls)
# Two-Stage Least Squares (TSLS) Use tsls (sem) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished