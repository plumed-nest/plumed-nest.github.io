**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[runnervmvrwv9:06300] *** Process received signal ***
[runnervmvrwv9:06300] Signal: Aborted (6)
[runnervmvrwv9:06300] Signal code:  (-6)
[runnervmvrwv9:06300] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb650045330]
[runnervmvrwv9:06300] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb65009eb2c]
[runnervmvrwv9:06300] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb65004527e]
[runnervmvrwv9:06300] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb6500288ff]
[runnervmvrwv9:06300] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb6504a5ff5]
[runnervmvrwv9:06300] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb6504bb0da]
[runnervmvrwv9:06300] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb6504a5a55]
[runnervmvrwv9:06300] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb6504a5a6f]
[runnervmvrwv9:06300] [ 8] plumed(+0x146dd)[0x55f31f2746dd]
[runnervmvrwv9:06300] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb65002a1ca]
[runnervmvrwv9:06300] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb65002a28b]
[runnervmvrwv9:06300] [11] plumed(+0x15365)[0x55f31f275365]
[runnervmvrwv9:06300] *** End of error message ***
</pre>
{% endraw %}
