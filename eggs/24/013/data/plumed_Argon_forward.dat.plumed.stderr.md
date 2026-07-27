**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmvrwv9:05086] *** Process received signal ***
[runnervmvrwv9:05086] Signal: Aborted (6)
[runnervmvrwv9:05086] Signal code:  (-6)
[runnervmvrwv9:05086] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5322e45330]
[runnervmvrwv9:05086] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5322e9eb2c]
[runnervmvrwv9:05086] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5322e4527e]
[runnervmvrwv9:05086] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5322e288ff]
[runnervmvrwv9:05086] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f53232a5ff5]
[runnervmvrwv9:05086] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f53232bb0da]
[runnervmvrwv9:05086] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f53232a5a55]
[runnervmvrwv9:05086] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f53232a5a6f]
[runnervmvrwv9:05086] [ 8] plumed(+0x146dd)[0x55a43c91b6dd]
[runnervmvrwv9:05086] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5322e2a1ca]
[runnervmvrwv9:05086] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5322e2a28b]
[runnervmvrwv9:05086] [11] plumed(+0x15365)[0x55a43c91c365]
[runnervmvrwv9:05086] *** End of error message ***
</pre>
{% endraw %}
