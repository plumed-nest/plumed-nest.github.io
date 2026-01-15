**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @49 : keyword ARG is compulsory for this action
[runnervmi13qx:38526] *** Process received signal ***
[runnervmi13qx:38526] Signal: Aborted (6)
[runnervmi13qx:38526] Signal code:  (-6)
[runnervmi13qx:38526] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fda1e645330]
[runnervmi13qx:38526] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fda1e69eb2c]
[runnervmi13qx:38526] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fda1e64527e]
[runnervmi13qx:38526] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fda1e6288ff]
[runnervmi13qx:38526] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fda1eaa5ff5]
[runnervmi13qx:38526] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fda1eabb0da]
[runnervmi13qx:38526] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fda1eaa5a55]
[runnervmi13qx:38526] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fda1eaa5a6f]
[runnervmi13qx:38526] [ 8] plumed_master(+0x146dd)[0x55d272d656dd]
[runnervmi13qx:38526] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fda1e62a1ca]
[runnervmi13qx:38526] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fda1e62a28b]
[runnervmi13qx:38526] [11] plumed_master(+0x15365)[0x55d272d66365]
[runnervmi13qx:38526] *** End of error message ***
</pre>
{% endraw %}
