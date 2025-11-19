# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Estimate and forecast the HAR (Heterogeneous Autoregressive) model and its extensions Use har (haR) With (In) R Software
install.packages("remotes")
remotes::install_github("daniGiro/haR")
library("haR")
haR = read.csv("https://raw.githubusercontent.com/timbulwidodostp/haR/main/haR/haR.csv",sep = ";")
# Estimation Estimate and forecast the HAR (Heterogeneous Autoregressive) model and its extensions Use har (haR) With (In) R Software
haR <- haR$haR
haR <- har(haR)
summary(haR)
# Estimate and forecast the HAR (Heterogeneous Autoregressive) model and its extensions Use har (haR) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished