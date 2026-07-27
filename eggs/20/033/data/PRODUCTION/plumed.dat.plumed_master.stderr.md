**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0, REF1, REF2
[runnervmvrwv9:09330] *** Process received signal ***
[runnervmvrwv9:09330] Signal: Aborted (6)
[runnervmvrwv9:09330] Signal code:  (-6)
[runnervmvrwv9:09330] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f01d2e45330]
[runnervmvrwv9:09330] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f01d2e9eb2c]
[runnervmvrwv9:09330] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f01d2e4527e]
[runnervmvrwv9:09330] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f01d2e288ff]
[runnervmvrwv9:09330] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f01d32a5ff5]
[runnervmvrwv9:09330] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f01d32bb0da]
[runnervmvrwv9:09330] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f01d32a5a55]
[runnervmvrwv9:09330] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f01d32a5a6f]
[runnervmvrwv9:09330] [ 8] plumed_master(+0x146dd)[0x562c0d1086dd]
[runnervmvrwv9:09330] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f01d2e2a1ca]
[runnervmvrwv9:09330] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f01d2e2a28b]
[runnervmvrwv9:09330] [11] plumed_master(+0x15365)[0x562c0d109365]
[runnervmvrwv9:09330] *** End of error message ***
</pre>
{% endraw %}
