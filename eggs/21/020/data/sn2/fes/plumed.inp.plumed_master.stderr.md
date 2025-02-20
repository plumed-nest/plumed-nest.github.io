**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @44 : keyword ARG is compulsory for this action
[fv-az816-356:11694] *** Process received signal ***
[fv-az816-356:11694] Signal: Aborted (6)
[fv-az816-356:11694] Signal code:  (-6)
[fv-az816-356:11694] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fda32645330]
[fv-az816-356:11694] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fda3269eb2c]
[fv-az816-356:11694] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fda3264527e]
[fv-az816-356:11694] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fda326288ff]
[fv-az816-356:11694] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fda32aa5ff5]
[fv-az816-356:11694] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fda32abb0da]
[fv-az816-356:11694] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fda32aa5a55]
[fv-az816-356:11694] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fda32aa5a6f]
[fv-az816-356:11694] [ 8] plumed_master(+0x146dd)[0x5582732f46dd]
[fv-az816-356:11694] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fda3262a1ca]
[fv-az816-356:11694] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fda3262a28b]
[fv-az816-356:11694] [11] plumed_master(+0x15365)[0x5582732f5365]
[fv-az816-356:11694] *** End of error message ***
</pre>
{% endraw %}
