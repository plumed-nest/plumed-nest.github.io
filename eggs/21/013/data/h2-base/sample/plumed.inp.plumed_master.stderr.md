**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-base/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[fv-az790-36:66095] *** Process received signal ***
[fv-az790-36:66095] Signal: Aborted (6)
[fv-az790-36:66095] Signal code:  (-6)
[fv-az790-36:66095] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7771045330]
[fv-az790-36:66095] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f777109eb2c]
[fv-az790-36:66095] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f777104527e]
[fv-az790-36:66095] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f77710288ff]
[fv-az790-36:66095] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f77714a5ff5]
[fv-az790-36:66095] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f77714bb0da]
[fv-az790-36:66095] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f77714a5a55]
[fv-az790-36:66095] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f77714a5a6f]
[fv-az790-36:66095] [ 8] plumed_master(+0x146dd)[0x559056f1b6dd]
[fv-az790-36:66095] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f777102a1ca]
[fv-az790-36:66095] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f777102a28b]
[fv-az790-36:66095] [11] plumed_master(+0x15365)[0x559056f1c365]
[fv-az790-36:66095] *** End of error message ***
</pre>
{% endraw %}
