**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @92 : keyword ARG is compulsory for this action
[fv-az1112-175:61994] *** Process received signal ***
[fv-az1112-175:61994] Signal: Aborted (6)
[fv-az1112-175:61994] Signal code:  (-6)
[fv-az1112-175:61994] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe46f045330]
[fv-az1112-175:61994] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe46f09eb2c]
[fv-az1112-175:61994] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe46f04527e]
[fv-az1112-175:61994] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe46f0288ff]
[fv-az1112-175:61994] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe46f4a5ff5]
[fv-az1112-175:61994] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe46f4bb0da]
[fv-az1112-175:61994] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe46f4a5a55]
[fv-az1112-175:61994] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe46f4a5a6f]
[fv-az1112-175:61994] [ 8] plumed_master(+0x146dd)[0x5645c467b6dd]
[fv-az1112-175:61994] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe46f02a1ca]
[fv-az1112-175:61994] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe46f02a28b]
[fv-az1112-175:61994] [11] plumed_master(+0x15365)[0x5645c467c365]
[fv-az1112-175:61994] *** End of error message ***
</pre>
{% endraw %}
