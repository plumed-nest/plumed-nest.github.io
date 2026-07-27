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
[runnervmvrwv9:08795] *** Process received signal ***
[runnervmvrwv9:08795] Signal: Aborted (6)
[runnervmvrwv9:08795] Signal code:  (-6)
[runnervmvrwv9:08795] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc6cfc45330]
[runnervmvrwv9:08795] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc6cfc9eb2c]
[runnervmvrwv9:08795] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc6cfc4527e]
[runnervmvrwv9:08795] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc6cfc288ff]
[runnervmvrwv9:08795] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc6d00a5ff5]
[runnervmvrwv9:08795] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc6d00bb0da]
[runnervmvrwv9:08795] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc6d00a5a55]
[runnervmvrwv9:08795] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc6d00a5a6f]
[runnervmvrwv9:08795] [ 8] plumed_master(+0x146dd)[0x55ca1d10b6dd]
[runnervmvrwv9:08795] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc6cfc2a1ca]
[runnervmvrwv9:08795] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc6cfc2a28b]
[runnervmvrwv9:08795] [11] plumed_master(+0x15365)[0x55ca1d10c365]
[runnervmvrwv9:08795] *** End of error message ***
</pre>
{% endraw %}
