# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Pseudo R2 Statistics Use PseudoR2 (DescTools) With (In) R Software
install.packages("DescTools")
library("DescTools")
# Estimate Pseudo R2 Statistics Use PseudoR2 (DescTools) With (In) R Software
PseudoR2 = read.csv("https://raw.githubusercontent.com/timbulwidodostp/PseudoR2/main/PseudoR2/PseudoR2.csv", sep = ";")
r.glm <- glm(Survived ~ Class + Sex + Age, data = PseudoR2, family=binomial)
PseudoR2 <- PseudoR2(r.glm, c("McFadden", "Nagel"))
PseudoR2
# Pseudo R2 Statistics Use PseudoR2 (DescTools) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished