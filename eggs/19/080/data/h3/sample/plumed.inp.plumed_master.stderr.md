**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[fv-az1719-82:69095] *** Process received signal ***
[fv-az1719-82:69095] Signal: Aborted (6)
[fv-az1719-82:69095] Signal code:  (-6)
[fv-az1719-82:69095] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdd26e45330]
[fv-az1719-82:69095] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdd26e9eb2c]
[fv-az1719-82:69095] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdd26e4527e]
[fv-az1719-82:69095] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdd26e288ff]
[fv-az1719-82:69095] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdd272a5ff5]
[fv-az1719-82:69095] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdd272bb0da]
[fv-az1719-82:69095] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdd272a5a55]
[fv-az1719-82:69095] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdd272a5a6f]
[fv-az1719-82:69095] [ 8] plumed_master(+0x146dd)[0x5600af66a6dd]
[fv-az1719-82:69095] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdd26e2a1ca]
[fv-az1719-82:69095] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdd26e2a28b]
[fv-az1719-82:69095] [11] plumed_master(+0x15365)[0x5600af66b365]
[fv-az1719-82:69095] *** End of error message ***
</pre>
{% endraw %}
