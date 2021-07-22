**Project ID:** [plumID:19.012]({{ '/' | absolute_url }}eggs/19/012/)  
Stderr for source:  ./Protein-DNA/plumed-main.dat   
(download [zipped raw stdout](plumed-main.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:128, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (saxsdata\.biasDer)
[fv-az95-172:72457] *** Process received signal ***
[fv-az95-172:72457] Signal: Aborted (6)
[fv-az95-172:72457] Signal code:  (-6)
[fv-az95-172:72457] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f58443ad210]
[fv-az95-172:72457] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f58443ad18b]
[fv-az95-172:72457] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f584438c859]
[fv-az95-172:72457] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f5844614911]
[fv-az95-172:72457] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f584462038c]
[fv-az95-172:72457] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f58446203f7]
[fv-az95-172:72457] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f58446206fd]
[fv-az95-172:72457] [ 7] plumed_master(+0xf5b5)[0x55e206d975b5]
[fv-az95-172:72457] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f584438e0b3]
[fv-az95-172:72457] [ 9] plumed_master(+0xf8be)[0x55e206d978be]
[fv-az95-172:72457] *** End of error message ***
</pre>
{% endraw %}
