**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmvrwv9:05164] *** Process received signal ***
[runnervmvrwv9:05164] Signal: Aborted (6)
[runnervmvrwv9:05164] Signal code:  (-6)
[runnervmvrwv9:05164] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f69ff645330]
[runnervmvrwv9:05164] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f69ff69eb2c]
[runnervmvrwv9:05164] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f69ff64527e]
[runnervmvrwv9:05164] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f69ff6288ff]
[runnervmvrwv9:05164] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f69ffaa5ff5]
[runnervmvrwv9:05164] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f69ffabb0da]
[runnervmvrwv9:05164] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f69ffaa5a55]
[runnervmvrwv9:05164] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f69ffaa5a6f]
[runnervmvrwv9:05164] [ 8] plumed_master(+0x146dd)[0x559cabc9a6dd]
[runnervmvrwv9:05164] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f69ff62a1ca]
[runnervmvrwv9:05164] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f69ff62a28b]
[runnervmvrwv9:05164] [11] plumed_master(+0x15365)[0x559cabc9b365]
[runnervmvrwv9:05164] *** End of error message ***
</pre>
{% endraw %}
