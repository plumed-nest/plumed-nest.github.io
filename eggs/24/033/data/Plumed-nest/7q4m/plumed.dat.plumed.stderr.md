**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervmeorf1:05165] *** Process received signal ***
[runnervmeorf1:05165] Signal: Aborted (6)
[runnervmeorf1:05165] Signal code:  (-6)
[runnervmeorf1:05165] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f98eb645330]
[runnervmeorf1:05165] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f98eb69eb2c]
[runnervmeorf1:05165] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f98eb64527e]
[runnervmeorf1:05165] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f98eb6288ff]
[runnervmeorf1:05165] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f98ebaa5ff5]
[runnervmeorf1:05165] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f98ebabb0da]
[runnervmeorf1:05165] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f98ebaa5a55]
[runnervmeorf1:05165] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f98ebaa5a6f]
[runnervmeorf1:05165] [ 8] plumed(+0x146dd)[0x561ee55886dd]
[runnervmeorf1:05165] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f98eb62a1ca]
[runnervmeorf1:05165] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f98eb62a28b]
[runnervmeorf1:05165] [11] plumed(+0x15365)[0x561ee5589365]
[runnervmeorf1:05165] *** End of error message ***
</pre>
{% endraw %}
