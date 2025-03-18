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
[fv-az790-36:62765] *** Process received signal ***
[fv-az790-36:62765] Signal: Aborted (6)
[fv-az790-36:62765] Signal code:  (-6)
[fv-az790-36:62765] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc124445330]
[fv-az790-36:62765] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc12449eb2c]
[fv-az790-36:62765] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc12444527e]
[fv-az790-36:62765] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc1244288ff]
[fv-az790-36:62765] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc1248a5ff5]
[fv-az790-36:62765] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc1248bb0da]
[fv-az790-36:62765] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc1248a5a55]
[fv-az790-36:62765] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc1248a5a6f]
[fv-az790-36:62765] [ 8] plumed_master(+0x146dd)[0x560e4d9f16dd]
[fv-az790-36:62765] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc12442a1ca]
[fv-az790-36:62765] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc12442a28b]
[fv-az790-36:62765] [11] plumed_master(+0x15365)[0x560e4d9f2365]
[fv-az790-36:62765] *** End of error message ***
</pre>
{% endraw %}
