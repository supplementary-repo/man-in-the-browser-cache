man-in-the-browser-cache
========================

man-in-the-browser-cache supplementary repo
Supplementary files for paper "Man-in-the-Browser-Cache: Persisting HTTPS Attacks via Browser Cache Poisoning".

The structure as follows:

ssl_warnings.pdf: The figure demonstrates SSL warnings in 21 mainstream browsers. As Figure 8a-8p show, SSL warnings in these browsers contain more content, e.g., certificate. The other browsers display incomplete information, e.g., missing the hijacked site’s URL, in the warning as shown in Figure 8q-8t.

address_bar_warnings.pdf: The figure shows warnings in the address bar on 21 mainstream browsers. As Figure 7a-7m show, if a browser has warnings for hijacked sites in the address bar, the upper one is the warning for sites over broken HTTPS and the lower one is for sites over securen HTTPS. Otherwise, the browser does not show any differences in the address bar, and the address bar always presents the same content for sites regardless of invalid certificates as shown in Figure 7n-7u.
