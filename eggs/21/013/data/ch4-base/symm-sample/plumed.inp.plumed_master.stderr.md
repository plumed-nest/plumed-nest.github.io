**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[fv-az1280-696:10835] *** Process received signal ***
[fv-az1280-696:10835] Signal: Aborted (6)
[fv-az1280-696:10835] Signal code:  (-6)
[fv-az1280-696:10835] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1277845330]
[fv-az1280-696:10835] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f127789eb2c]
[fv-az1280-696:10835] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f127784527e]
[fv-az1280-696:10835] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f12778288ff]
[fv-az1280-696:10835] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1277ca5ff5]
[fv-az1280-696:10835] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1277cbb0da]
[fv-az1280-696:10835] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1277ca5a55]
[fv-az1280-696:10835] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1277ca5a6f]
[fv-az1280-696:10835] [ 8] plumed_master(+0x146dd)[0x564124ed96dd]
[fv-az1280-696:10835] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f127782a1ca]
[fv-az1280-696:10835] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f127782a28b]
[fv-az1280-696:10835] [11] plumed_master(+0x15365)[0x564124eda365]
[fv-az1280-696:10835] *** End of error message ***
</pre>
{% endraw %}
