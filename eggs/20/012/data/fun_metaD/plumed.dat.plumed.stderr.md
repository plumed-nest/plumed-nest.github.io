**Project ID:** [plumID:20.012]({{ '/' | absolute_url }}eggs/20/012/)  
Stderr for source:  fun_metaD/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PROJECTION_ON_AXIS LABEL=pp AXIS_ATOMS=p1,p2_FS2 ATOM=lig
Maybe a missing space or a typo?
[fv-az95-172:52526] *** Process received signal ***
[fv-az95-172:52526] Signal: Aborted (6)
[fv-az95-172:52526] Signal code:  (-6)
[fv-az95-172:52526] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f1006b46210]
[fv-az95-172:52526] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f1006b4618b]
[fv-az95-172:52526] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f1006b25859]
[fv-az95-172:52526] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f1006dad911]
[fv-az95-172:52526] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f1006db938c]
[fv-az95-172:52526] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f1006db93f7]
[fv-az95-172:52526] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f1006db96a9]
[fv-az95-172:52526] [ 7] plumed(+0xf47d)[0x562e001c147d]
[fv-az95-172:52526] [ 8] plumed(+0x14004)[0x562e001c6004]
[fv-az95-172:52526] [ 9] plumed(+0xf698)[0x562e001c1698]
[fv-az95-172:52526] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f1006b270b3]
[fv-az95-172:52526] [11] plumed(+0xf76e)[0x562e001c176e]
[fv-az95-172:52526] *** End of error message ***
</pre>
{% endraw %}
