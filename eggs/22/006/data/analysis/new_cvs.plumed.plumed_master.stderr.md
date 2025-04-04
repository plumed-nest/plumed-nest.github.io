**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @94 : keyword ARG is compulsory for this action
[fv-az1624-565:07239] *** Process received signal ***
[fv-az1624-565:07239] Signal: Aborted (6)
[fv-az1624-565:07239] Signal code:  (-6)
[fv-az1624-565:07239] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7facb4845330]
[fv-az1624-565:07239] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7facb489eb2c]
[fv-az1624-565:07239] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7facb484527e]
[fv-az1624-565:07239] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7facb48288ff]
[fv-az1624-565:07239] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7facb4ca5ff5]
[fv-az1624-565:07239] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7facb4cbb0da]
[fv-az1624-565:07239] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7facb4ca5a55]
[fv-az1624-565:07239] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7facb4ca5a6f]
[fv-az1624-565:07239] [ 8] plumed_master(+0x146dd)[0x561708c906dd]
[fv-az1624-565:07239] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7facb482a1ca]
[fv-az1624-565:07239] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7facb482a28b]
[fv-az1624-565:07239] [11] plumed_master(+0x15365)[0x561708c91365]
[fv-az1624-565:07239] *** End of error message ***
</pre>
{% endraw %}
