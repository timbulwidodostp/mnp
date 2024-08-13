# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fitting the Multinomial Probit Model via Markov chain Monte Carlo Use MNP With (In) R Software
install.packages("MNP")
library("MNP")
mnp = read.csv("https://raw.githubusercontent.com/timbulwidodostp/mnp/main/mnp/mnp.csv",sep = ";")
# Estimation Fitting the Multinomial Probit Model via Markov chain Monte Carlo Use MNP With (In) R Software
mnp_1 <- mnp(cbind(LDP, NFP, SKG, JCP) ~ gender + education + age, data = mnp)
summary(mnp_1)
mnp_2 <- mnp(cbind(LDP, NFP, SKG, JCP) ~ gender + education + age, data = mnp, verbose = TRUE)
summary(mnp_2)
# Fitting the Multinomial Probit Model via Markov chain Monte Carlo Use MNP With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished