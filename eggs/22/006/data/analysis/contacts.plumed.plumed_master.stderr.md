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
[fv-az1911-722:07185] *** Process received signal ***
[fv-az1911-722:07185] Signal: Aborted (6)
[fv-az1911-722:07185] Signal code:  (-6)
[fv-az1911-722:07185] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0ddac45330]
[fv-az1911-722:07185] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0ddac9eb2c]
[fv-az1911-722:07185] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0ddac4527e]
[fv-az1911-722:07185] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0ddac288ff]
[fv-az1911-722:07185] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0ddb0a5ff5]
[fv-az1911-722:07185] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0ddb0bb0da]
[fv-az1911-722:07185] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0ddb0a5a55]
[fv-az1911-722:07185] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0ddb0a5a6f]
[fv-az1911-722:07185] [ 8] plumed_master(+0x146dd)[0x55b0a90fc6dd]
[fv-az1911-722:07185] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0ddac2a1ca]
[fv-az1911-722:07185] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0ddac2a28b]
[fv-az1911-722:07185] [11] plumed_master(+0x15365)[0x55b0a90fd365]
[fv-az1911-722:07185] *** End of error message ***
</pre>
{% endraw %}
