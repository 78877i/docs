bc1qu0xvwp0cvglxmsc6lyyw6tktdlvlspta506mrd#N монада, monad.swb.de, monad.swb.sub.org
#S В 486DX50; Линукс 0.99
#О частный
#C Олаф Кирх
#E okir@monad.swb.de
#P Kattreinstr. 38, D-64295 Дармштадт, ФРГ
#L 49 52 03 Н / 08 38 40 В
#ты варишь
#W okir@monad.swb.de (Олаф Кирх); Вс, 25 июля, 16:59:32 MET DST 1993
#
monad brewhq(ЕЖЕДНЕВНО/2)
# Домены
монада = monad.swb.de
монада = monad.swb.sub.org--
title: Sudo mode
intro: '{% data variables.product.product_name %} asks you for your password before you can modify your email address, authorize third-party applications, or add new public keys, or initiate other *sudo-protected* actions.'
redirect_from:
  - /articles/sudo-mode
  - /github/authenticating-to-github/sudo-mode
  - /github/authenticating-to-github/keeping-your-account-and-data-secure/sudo-mode
versions:
  fpt: '*'
  ghes: '*'
  ghec: '*'
topics:
  - Identity
  - Access management
---
After you've performed a sudo-protected action, you'll only be asked to re-authenticate again after a few hours of inactivity. Every sudo-protected action resets this timer.

![Sudo Mode Dialog](/assets/images/help/settings/sudo_mode_popup.png)

## Further reading

- [Unix `sudo` command](http://en.wikipedia.org/wiki/Sudo)
