**Project ID:** [plumID:21.040]({{ '/' | absolute_url }}eggs/21/040/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @38 : cannot understand the following words from the input line : REF0, REF1, REF10, REF11, REF12, REF13, REF14, REF15, REF16, REF17, REF18, REF19, REF2, REF20, REF21, REF22, REF23, REF24, REF25, REF26, REF27, REF28, REF3, REF4, REF5, REF6, REF7, REF8, REF9
[runnervmmklqx:07619] *** Process received signal ***
[runnervmmklqx:07619] Signal: Aborted (6)
[runnervmmklqx:07619] Signal code:  (-6)
[runnervmmklqx:07619] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4c35045330]
[runnervmmklqx:07619] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4c3509eb2c]
[runnervmmklqx:07619] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4c3504527e]
[runnervmmklqx:07619] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4c350288ff]
[runnervmmklqx:07619] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4c354a5ff5]
[runnervmmklqx:07619] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4c354bb0da]
[runnervmmklqx:07619] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4c354a5a55]
[runnervmmklqx:07619] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4c354a5a6f]
[runnervmmklqx:07619] [ 8] plumed_master(+0x146dd)[0x560dd5e816dd]
[runnervmmklqx:07619] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4c3502a1ca]
[runnervmmklqx:07619] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4c3502a28b]
[runnervmmklqx:07619] [11] plumed_master(+0x15365)[0x560dd5e82365]
[runnervmmklqx:07619] *** End of error message ***
</pre>
{% endraw %}
