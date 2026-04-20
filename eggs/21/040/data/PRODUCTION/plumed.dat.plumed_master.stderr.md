**Project ID:** [plumID:21.040]({{ '/' | absolute_url }}eggs/21/040/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @38 : cannot understand the following words from the input line : REF0, REF1, REF10, REF11, REF12, REF13, REF14, REF15, REF16, REF17, REF18, REF19, REF2, REF20, REF21, REF22, REF23, REF24, REF25, REF26, REF27, REF28, REF3, REF4, REF5, REF6, REF7, REF8, REF9
[runnervmeorf1:08576] *** Process received signal ***
[runnervmeorf1:08576] Signal: Aborted (6)
[runnervmeorf1:08576] Signal code:  (-6)
[runnervmeorf1:08576] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd11b045330]
[runnervmeorf1:08576] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd11b09eb2c]
[runnervmeorf1:08576] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd11b04527e]
[runnervmeorf1:08576] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd11b0288ff]
[runnervmeorf1:08576] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd11b4a5ff5]
[runnervmeorf1:08576] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd11b4bb0da]
[runnervmeorf1:08576] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd11b4a5a55]
[runnervmeorf1:08576] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd11b4a5a6f]
[runnervmeorf1:08576] [ 8] plumed_master(+0x146dd)[0x561065f5d6dd]
[runnervmeorf1:08576] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd11b02a1ca]
[runnervmeorf1:08576] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd11b02a28b]
[runnervmeorf1:08576] [11] plumed_master(+0x15365)[0x561065f5e365]
[runnervmeorf1:08576] *** End of error message ***
</pre>
{% endraw %}
