**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmvrwv9:05000] *** Process received signal ***
[runnervmvrwv9:05000] Signal: Aborted (6)
[runnervmvrwv9:05000] Signal code:  (-6)
[runnervmvrwv9:05000] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6465045330]
[runnervmvrwv9:05000] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f646509eb2c]
[runnervmvrwv9:05000] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f646504527e]
[runnervmvrwv9:05000] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f64650288ff]
[runnervmvrwv9:05000] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f64654a5ff5]
[runnervmvrwv9:05000] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f64654bb0da]
[runnervmvrwv9:05000] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f64654a5a55]
[runnervmvrwv9:05000] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f64654a5a6f]
[runnervmvrwv9:05000] [ 8] plumed(+0x146dd)[0x557db9bf16dd]
[runnervmvrwv9:05000] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f646502a1ca]
[runnervmvrwv9:05000] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f646502a28b]
[runnervmvrwv9:05000] [11] plumed(+0x15365)[0x557db9bf2365]
[runnervmvrwv9:05000] *** End of error message ***
</pre>
{% endraw %}
