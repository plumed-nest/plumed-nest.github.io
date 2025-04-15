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
[fv-az1921-959:69028] *** Process received signal ***
[fv-az1921-959:69028] Signal: Aborted (6)
[fv-az1921-959:69028] Signal code:  (-6)
[fv-az1921-959:69028] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd845845330]
[fv-az1921-959:69028] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd84589eb2c]
[fv-az1921-959:69028] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd84584527e]
[fv-az1921-959:69028] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd8458288ff]
[fv-az1921-959:69028] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd845ca5ff5]
[fv-az1921-959:69028] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd845cbb0da]
[fv-az1921-959:69028] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd845ca5a55]
[fv-az1921-959:69028] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd845ca5a6f]
[fv-az1921-959:69028] [ 8] plumed_master(+0x146dd)[0x558c948856dd]
[fv-az1921-959:69028] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd84582a1ca]
[fv-az1921-959:69028] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd84582a28b]
[fv-az1921-959:69028] [11] plumed_master(+0x15365)[0x558c94886365]
[fv-az1921-959:69028] *** End of error message ***
</pre>
{% endraw %}
