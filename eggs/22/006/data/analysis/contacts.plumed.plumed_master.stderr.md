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
[fv-az1047-397:63912] *** Process received signal ***
[fv-az1047-397:63912] Signal: Aborted (6)
[fv-az1047-397:63912] Signal code:  (-6)
[fv-az1047-397:63912] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbacf845330]
[fv-az1047-397:63912] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbacf89eb2c]
[fv-az1047-397:63912] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbacf84527e]
[fv-az1047-397:63912] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbacf8288ff]
[fv-az1047-397:63912] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbacfca5ff5]
[fv-az1047-397:63912] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbacfcbb0da]
[fv-az1047-397:63912] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbacfca5a55]
[fv-az1047-397:63912] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbacfca5a6f]
[fv-az1047-397:63912] [ 8] plumed_master(+0x146dd)[0x55dd05b516dd]
[fv-az1047-397:63912] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbacf82a1ca]
[fv-az1047-397:63912] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbacf82a28b]
[fv-az1047-397:63912] [11] plumed_master(+0x15365)[0x55dd05b52365]
[fv-az1047-397:63912] *** End of error message ***
</pre>
{% endraw %}
