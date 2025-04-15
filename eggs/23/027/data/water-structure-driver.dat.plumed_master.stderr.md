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
[fv-az1693-957:63387] *** Process received signal ***
[fv-az1693-957:63387] Signal: Aborted (6)
[fv-az1693-957:63387] Signal code:  (-6)
[fv-az1693-957:63387] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1d06045330]
[fv-az1693-957:63387] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1d0609eb2c]
[fv-az1693-957:63387] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1d0604527e]
[fv-az1693-957:63387] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1d060288ff]
[fv-az1693-957:63387] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1d064a5ff5]
[fv-az1693-957:63387] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1d064bb0da]
[fv-az1693-957:63387] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1d064a5a55]
[fv-az1693-957:63387] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1d064a5a6f]
[fv-az1693-957:63387] [ 8] plumed_master(+0x146dd)[0x5607bf3f06dd]
[fv-az1693-957:63387] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1d0602a1ca]
[fv-az1693-957:63387] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1d0602a28b]
[fv-az1693-957:63387] [11] plumed_master(+0x15365)[0x5607bf3f1365]
[fv-az1693-957:63387] *** End of error message ***
</pre>
{% endraw %}
