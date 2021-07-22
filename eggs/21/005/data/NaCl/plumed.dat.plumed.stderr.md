**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
Stderr for source:  NaCl/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTORCH_MODEL LABEL=auto1 MODEL=nacl_sfNa_ct1.pt ARG=s1.Sk3_-3_-3,s1.Sk3_-3_3,s1.Sk3_3_-3,s1.Sk3_3_3,s1.Sk6_0_0,s1.Sk0_6_-6,s1.Sk0_6_6,s1.Sk6_-6_0,s1.Sk6_0_-6,s1.Sk6_0_6,s1.Sk6_6_0,s1.Sk9_-3_-3,s1.Sk9_-3_3,s1.Sk9_3_-3,s1.Sk9_3_3
Maybe a missing space or a typo?
[fv-az95-172:46539] *** Process received signal ***
[fv-az95-172:46539] Signal: Aborted (6)
[fv-az95-172:46539] Signal code:  (-6)
[fv-az95-172:46539] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f9761a0b210]
[fv-az95-172:46539] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f9761a0b18b]
[fv-az95-172:46539] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f97619ea859]
[fv-az95-172:46539] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f9761c72911]
[fv-az95-172:46539] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f9761c7e38c]
[fv-az95-172:46539] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f9761c7e3f7]
[fv-az95-172:46539] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f9761c7e6a9]
[fv-az95-172:46539] [ 7] plumed(+0xf47d)[0x55cf36cf247d]
[fv-az95-172:46539] [ 8] plumed(+0x14004)[0x55cf36cf7004]
[fv-az95-172:46539] [ 9] plumed(+0xf698)[0x55cf36cf2698]
[fv-az95-172:46539] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f97619ec0b3]
[fv-az95-172:46539] [11] plumed(+0xf76e)[0x55cf36cf276e]
[fv-az95-172:46539] *** End of error message ***
</pre>
{% endraw %}
