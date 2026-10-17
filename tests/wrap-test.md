# Wrap order test

| case | construction | icon |
|---|---|---|
| W0 | unlinked control | <img src="../assets/arrow-left.svg#gh-light-mode-only" width="32" alt="L"><img src="../assets/arrow-left-white.svg#gh-dark-mode-only" width="32" alt="D"> |
| W1 | suffix anchor around img, wrapped by real link | <a href="pg-2.md"><a href="../assets/arrow-left.svg#gh-light-mode-only"><img src="../assets/arrow-left.svg" width="32" alt="L"></a><a href="../assets/arrow-left-white.svg#gh-dark-mode-only"><img src="../assets/arrow-left-white.svg" width="32" alt="D"></a></a> |
| W2 | markdown image links | [![L](../assets/arrow-left.svg#gh-light-mode-only)](pg-2.md)[![D](../assets/arrow-left-white.svg#gh-dark-mode-only)](pg-2.md) |
| W3 | suffix on the link href itself | <a href="pg-2.md#gh-light-mode-only"><img src="../assets/arrow-left.svg" width="32" alt="L"></a><a href="pg-2.md#gh-dark-mode-only"><img src="../assets/arrow-left-white.svg" width="32" alt="D"></a> |
| W4 | real link, outer; suffix img inside span | <a href="pg-2.md"><span><img src="../assets/arrow-left.svg#gh-light-mode-only" width="32" alt="L"></span><span><img src="../assets/arrow-left-white.svg#gh-dark-mode-only" width="32" alt="D"></span></a> |
| W5 | double fragment (anchor id plus suffix) | <a href="glossary.md#g-fill-base#gh-light-mode-only"><img src="../assets/arrow-down.svg" width="32" alt="L"></a><a href="glossary.md#g-fill-base#gh-dark-mode-only"><img src="../assets/arrow-down-white.svg" width="32" alt="D"></a> |
