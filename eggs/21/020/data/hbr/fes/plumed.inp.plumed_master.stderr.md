**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @41 : keyword ARG is compulsory for this action
[runnervmmtnos:34162] *** Process received signal ***
[runnervmmtnos:34162] Signal: Aborted (6)
[runnervmmtnos:34162] Signal code:  (-6)
[runnervmmtnos:34162] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f007de45330]
[runnervmmtnos:34162] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f007de9eb2c]
[runnervmmtnos:34162] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f007de4527e]
[runnervmmtnos:34162] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f007de288ff]
[runnervmmtnos:34162] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f007e2a5ff5]
[runnervmmtnos:34162] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f007e2bb0da]
[runnervmmtnos:34162] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f007e2a5a55]
[runnervmmtnos:34162] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f007e2a5a6f]
[runnervmmtnos:34162] [ 8] plumed_master(+0x146dd)[0x55d558a3e6dd]
[runnervmmtnos:34162] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f007de2a1ca]
[runnervmmtnos:34162] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f007de2a28b]
[runnervmmtnos:34162] [11] plumed_master(+0x15365)[0x55d558a3f365]
[runnervmmtnos:34162] *** End of error message ***
</pre>
{% endraw %}
