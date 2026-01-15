**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ch-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @25 : keyword ARG is compulsory for this action
[runnervmi13qx:38088] *** Process received signal ***
[runnervmi13qx:38088] Signal: Aborted (6)
[runnervmi13qx:38088] Signal code:  (-6)
[runnervmi13qx:38088] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbbea245330]
[runnervmi13qx:38088] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbbea29eb2c]
[runnervmi13qx:38088] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbbea24527e]
[runnervmi13qx:38088] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbbea2288ff]
[runnervmi13qx:38088] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbbea6a5ff5]
[runnervmi13qx:38088] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbbea6bb0da]
[runnervmi13qx:38088] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbbea6a5a55]
[runnervmi13qx:38088] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbbea6a5a6f]
[runnervmi13qx:38088] [ 8] plumed_master(+0x146dd)[0x56276f1856dd]
[runnervmi13qx:38088] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbbea22a1ca]
[runnervmi13qx:38088] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbbea22a28b]
[runnervmi13qx:38088] [11] plumed_master(+0x15365)[0x56276f186365]
[runnervmi13qx:38088] *** End of error message ***
</pre>
{% endraw %}
