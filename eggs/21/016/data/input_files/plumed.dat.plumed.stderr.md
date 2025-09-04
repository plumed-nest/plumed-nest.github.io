**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[pkrvm7jw40e0xgp:10669] *** Process received signal ***
[pkrvm7jw40e0xgp:10669] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10669] Signal code:  (-6)
[pkrvm7jw40e0xgp:10669] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f825fc45330]
[pkrvm7jw40e0xgp:10669] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f825fc9eb2c]
[pkrvm7jw40e0xgp:10669] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f825fc4527e]
[pkrvm7jw40e0xgp:10669] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f825fc288ff]
[pkrvm7jw40e0xgp:10669] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f82600a5ff5]
[pkrvm7jw40e0xgp:10669] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f82600bb0da]
[pkrvm7jw40e0xgp:10669] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f82600a5a55]
[pkrvm7jw40e0xgp:10669] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f82600a5a6f]
[pkrvm7jw40e0xgp:10669] [ 8] plumed(+0x146dd)[0x5579ef7f26dd]
[pkrvm7jw40e0xgp:10669] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f825fc2a1ca]
[pkrvm7jw40e0xgp:10669] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f825fc2a28b]
[pkrvm7jw40e0xgp:10669] [11] plumed(+0x15365)[0x5579ef7f3365]
[pkrvm7jw40e0xgp:10669] *** End of error message ***
</pre>
{% endraw %}
