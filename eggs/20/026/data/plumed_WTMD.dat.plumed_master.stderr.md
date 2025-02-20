**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @79 : keyword ARG is compulsory for this action
[fv-az816-356:12357] *** Process received signal ***
[fv-az816-356:12357] Signal: Aborted (6)
[fv-az816-356:12357] Signal code:  (-6)
[fv-az816-356:12357] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc6f3e45330]
[fv-az816-356:12357] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc6f3e9eb2c]
[fv-az816-356:12357] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc6f3e4527e]
[fv-az816-356:12357] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc6f3e288ff]
[fv-az816-356:12357] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc6f42a5ff5]
[fv-az816-356:12357] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc6f42bb0da]
[fv-az816-356:12357] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc6f42a5a55]
[fv-az816-356:12357] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc6f42a5a6f]
[fv-az816-356:12357] [ 8] plumed_master(+0x146dd)[0x55925a2c76dd]
[fv-az816-356:12357] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc6f3e2a1ca]
[fv-az816-356:12357] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc6f3e2a28b]
[fv-az816-356:12357] [11] plumed_master(+0x15365)[0x55925a2c8365]
[fv-az816-356:12357] *** End of error message ***
</pre>
{% endraw %}
