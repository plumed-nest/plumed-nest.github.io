**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[runnervmmtnos:34099] *** Process received signal ***
[runnervmmtnos:34099] Signal: Aborted (6)
[runnervmmtnos:34099] Signal code:  (-6)
[runnervmmtnos:34099] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f259b645330]
[runnervmmtnos:34099] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f259b69eb2c]
[runnervmmtnos:34099] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f259b64527e]
[runnervmmtnos:34099] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f259b6288ff]
[runnervmmtnos:34099] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f259baa5ff5]
[runnervmmtnos:34099] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f259babb0da]
[runnervmmtnos:34099] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f259baa5a55]
[runnervmmtnos:34099] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f259baa5a6f]
[runnervmmtnos:34099] [ 8] plumed_master(+0x146dd)[0x563f816c16dd]
[runnervmmtnos:34099] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f259b62a1ca]
[runnervmmtnos:34099] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f259b62a28b]
[runnervmmtnos:34099] [11] plumed_master(+0x15365)[0x563f816c2365]
[runnervmmtnos:34099] *** End of error message ***
</pre>
{% endraw %}
