**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @92 : keyword ARG is compulsory for this action
[fv-az1374-136:64429] *** Process received signal ***
[fv-az1374-136:64429] Signal: Aborted (6)
[fv-az1374-136:64429] Signal code:  (-6)
[fv-az1374-136:64429] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fccb1845330]
[fv-az1374-136:64429] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fccb189eb2c]
[fv-az1374-136:64429] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fccb184527e]
[fv-az1374-136:64429] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fccb18288ff]
[fv-az1374-136:64429] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fccb1ca5ff5]
[fv-az1374-136:64429] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fccb1cbb0da]
[fv-az1374-136:64429] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fccb1ca5a55]
[fv-az1374-136:64429] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fccb1ca5a6f]
[fv-az1374-136:64429] [ 8] plumed_master(+0x146dd)[0x56347db3b6dd]
[fv-az1374-136:64429] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fccb182a1ca]
[fv-az1374-136:64429] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fccb182a28b]
[fv-az1374-136:64429] [11] plumed_master(+0x15365)[0x56347db3c365]
[fv-az1374-136:64429] *** End of error message ***
</pre>
{% endraw %}
