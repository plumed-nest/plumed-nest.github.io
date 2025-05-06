**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  water-structure-driver.dat   
Download: [zipped raw stdout](water-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](water-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @173 : keyword ARG is compulsory for this action
[fv-az1278-681:61795] *** Process received signal ***
[fv-az1278-681:61795] Signal: Aborted (6)
[fv-az1278-681:61795] Signal code:  (-6)
[fv-az1278-681:61795] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb0dc645330]
[fv-az1278-681:61795] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb0dc69eb2c]
[fv-az1278-681:61795] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb0dc64527e]
[fv-az1278-681:61795] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb0dc6288ff]
[fv-az1278-681:61795] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb0dcaa5ff5]
[fv-az1278-681:61795] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb0dcabb0da]
[fv-az1278-681:61795] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb0dcaa5a55]
[fv-az1278-681:61795] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb0dcaa5a6f]
[fv-az1278-681:61795] [ 8] plumed_master(+0x146dd)[0x5567ba5486dd]
[fv-az1278-681:61795] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb0dc62a1ca]
[fv-az1278-681:61795] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb0dc62a28b]
[fv-az1278-681:61795] [11] plumed_master(+0x15365)[0x5567ba549365]
[fv-az1278-681:61795] *** End of error message ***
</pre>
{% endraw %}
