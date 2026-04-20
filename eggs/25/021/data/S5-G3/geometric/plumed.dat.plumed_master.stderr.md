**Project ID:** [plumID:25.021]({{ '/' | absolute_url }}eggs/25/021/)  
Stderr for source:  S5-G3/geometric/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action FIT_TO_TEMPLATE with label @8 : missing input file conf_template.pdb
[runnervmeorf1:05356] *** Process received signal ***
[runnervmeorf1:05356] Signal: Aborted (6)
[runnervmeorf1:05356] Signal code:  (-6)
[runnervmeorf1:05356] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe3a9c45330]
[runnervmeorf1:05356] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe3a9c9eb2c]
[runnervmeorf1:05356] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe3a9c4527e]
[runnervmeorf1:05356] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe3a9c288ff]
[runnervmeorf1:05356] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe3aa0a5ff5]
[runnervmeorf1:05356] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe3aa0bb0da]
[runnervmeorf1:05356] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe3aa0a5a55]
[runnervmeorf1:05356] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe3aa0a5a6f]
[runnervmeorf1:05356] [ 8] plumed_master(+0x146dd)[0x558218fdf6dd]
[runnervmeorf1:05356] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe3a9c2a1ca]
[runnervmeorf1:05356] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe3a9c2a28b]
[runnervmeorf1:05356] [11] plumed_master(+0x15365)[0x558218fe0365]
[runnervmeorf1:05356] *** End of error message ***
</pre>
{% endraw %}
