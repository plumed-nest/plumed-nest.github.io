**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[fv-az1691-811:10316] *** Process received signal ***
[fv-az1691-811:10316] Signal: Aborted (6)
[fv-az1691-811:10316] Signal code:  (-6)
[fv-az1691-811:10316] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe27c845330]
[fv-az1691-811:10316] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe27c89eb2c]
[fv-az1691-811:10316] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe27c84527e]
[fv-az1691-811:10316] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe27c8288ff]
[fv-az1691-811:10316] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe27cca5ff5]
[fv-az1691-811:10316] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe27ccbb0da]
[fv-az1691-811:10316] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe27cca5a55]
[fv-az1691-811:10316] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe27cca5a6f]
[fv-az1691-811:10316] [ 8] plumed_master(+0x146dd)[0x55ed4d89b6dd]
[fv-az1691-811:10316] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe27c82a1ca]
[fv-az1691-811:10316] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe27c82a28b]
[fv-az1691-811:10316] [11] plumed_master(+0x15365)[0x55ed4d89c365]
[fv-az1691-811:10316] *** End of error message ***
</pre>
{% endraw %}
