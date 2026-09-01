**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
Download: [zipped raw stdout](plumed_REWE.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_REWE.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID, REWEIGHTING_NHILLS
[runnervmgx7h7:10905] *** Process received signal ***
[runnervmgx7h7:10905] Signal: Aborted (6)
[runnervmgx7h7:10905] Signal code:  (-6)
[runnervmgx7h7:10905] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0a5b845330]
[runnervmgx7h7:10905] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0a5b89ec0c]
[runnervmgx7h7:10905] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0a5b84527e]
[runnervmgx7h7:10905] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0a5b8288ff]
[runnervmgx7h7:10905] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0a5bca5ff5]
[runnervmgx7h7:10905] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0a5bcbb0da]
[runnervmgx7h7:10905] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0a5bca5a55]
[runnervmgx7h7:10905] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0a5bca5a6f]
[runnervmgx7h7:10905] [ 8] plumed_master(+0x146dd)[0x55629b3036dd]
[runnervmgx7h7:10905] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0a5b82a1ca]
[runnervmgx7h7:10905] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0a5b82a28b]
[runnervmgx7h7:10905] [11] plumed_master(+0x15365)[0x55629b304365]
[runnervmgx7h7:10905] *** End of error message ***
</pre>
{% endraw %}
