**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmvrwv9:05019] *** Process received signal ***
[runnervmvrwv9:05019] Signal: Aborted (6)
[runnervmvrwv9:05019] Signal code:  (-6)
[runnervmvrwv9:05019] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fad02645330]
[runnervmvrwv9:05019] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fad0269eb2c]
[runnervmvrwv9:05019] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fad0264527e]
[runnervmvrwv9:05019] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fad026288ff]
[runnervmvrwv9:05019] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fad02aa5ff5]
[runnervmvrwv9:05019] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fad02abb0da]
[runnervmvrwv9:05019] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fad02aa5a55]
[runnervmvrwv9:05019] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fad02aa5a6f]
[runnervmvrwv9:05019] [ 8] plumed_master(+0x146dd)[0x5626674226dd]
[runnervmvrwv9:05019] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fad0262a1ca]
[runnervmvrwv9:05019] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fad0262a28b]
[runnervmvrwv9:05019] [11] plumed_master(+0x15365)[0x562667423365]
[runnervmvrwv9:05019] *** End of error message ***
</pre>
{% endraw %}
