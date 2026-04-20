**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0, REF1, REF2
[runnervmeorf1:09195] *** Process received signal ***
[runnervmeorf1:09195] Signal: Aborted (6)
[runnervmeorf1:09195] Signal code:  (-6)
[runnervmeorf1:09195] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe453e45330]
[runnervmeorf1:09195] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe453e9eb2c]
[runnervmeorf1:09195] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe453e4527e]
[runnervmeorf1:09195] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe453e288ff]
[runnervmeorf1:09195] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe4542a5ff5]
[runnervmeorf1:09195] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe4542bb0da]
[runnervmeorf1:09195] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe4542a5a55]
[runnervmeorf1:09195] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe4542a5a6f]
[runnervmeorf1:09195] [ 8] plumed_master(+0x146dd)[0x562a72d666dd]
[runnervmeorf1:09195] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe453e2a1ca]
[runnervmeorf1:09195] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe453e2a28b]
[runnervmeorf1:09195] [11] plumed_master(+0x15365)[0x562a72d67365]
[runnervmeorf1:09195] *** End of error message ***
</pre>
{% endraw %}
