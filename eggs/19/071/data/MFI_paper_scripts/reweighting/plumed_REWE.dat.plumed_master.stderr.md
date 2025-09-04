**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
Download: [zipped raw stdout](plumed_REWE.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_REWE.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[pkrvm7jw40e0xgp:13035] *** Process received signal ***
[pkrvm7jw40e0xgp:13035] Signal: Aborted (6)
[pkrvm7jw40e0xgp:13035] Signal code:  (-6)
[pkrvm7jw40e0xgp:13035] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f71bea45330]
[pkrvm7jw40e0xgp:13035] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f71bea9eb2c]
[pkrvm7jw40e0xgp:13035] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f71bea4527e]
[pkrvm7jw40e0xgp:13035] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f71bea288ff]
[pkrvm7jw40e0xgp:13035] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f71beea5ff5]
[pkrvm7jw40e0xgp:13035] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f71beebb0da]
[pkrvm7jw40e0xgp:13035] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f71beea5a55]
[pkrvm7jw40e0xgp:13035] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f71beea5a6f]
[pkrvm7jw40e0xgp:13035] [ 8] plumed_master(+0x146dd)[0x55b0f9d0d6dd]
[pkrvm7jw40e0xgp:13035] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f71bea2a1ca]
[pkrvm7jw40e0xgp:13035] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f71bea2a28b]
[pkrvm7jw40e0xgp:13035] [11] plumed_master(+0x15365)[0x55b0f9d0e365]
[pkrvm7jw40e0xgp:13035] *** End of error message ***
</pre>
{% endraw %}
