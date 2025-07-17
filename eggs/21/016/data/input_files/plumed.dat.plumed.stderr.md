**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[pkrvmq0rgcvqdmg:09432] *** Process received signal ***
[pkrvmq0rgcvqdmg:09432] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09432] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09432] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fca5f445330]
[pkrvmq0rgcvqdmg:09432] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fca5f49eb2c]
[pkrvmq0rgcvqdmg:09432] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fca5f44527e]
[pkrvmq0rgcvqdmg:09432] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fca5f4288ff]
[pkrvmq0rgcvqdmg:09432] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fca5f8a5ff5]
[pkrvmq0rgcvqdmg:09432] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fca5f8bb0da]
[pkrvmq0rgcvqdmg:09432] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fca5f8a5a55]
[pkrvmq0rgcvqdmg:09432] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fca5f8a5a6f]
[pkrvmq0rgcvqdmg:09432] [ 8] plumed(+0x146dd)[0x55d10fe546dd]
[pkrvmq0rgcvqdmg:09432] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fca5f42a1ca]
[pkrvmq0rgcvqdmg:09432] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fca5f42a28b]
[pkrvmq0rgcvqdmg:09432] [11] plumed(+0x15365)[0x55d10fe55365]
[pkrvmq0rgcvqdmg:09432] *** End of error message ***
</pre>
{% endraw %}
