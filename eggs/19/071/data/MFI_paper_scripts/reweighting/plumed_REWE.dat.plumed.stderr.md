**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
Download: [zipped raw stdout](plumed_REWE.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_REWE.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[runnervmvrwv9:10324] *** Process received signal ***
[runnervmvrwv9:10324] Signal: Aborted (6)
[runnervmvrwv9:10324] Signal code:  (-6)
[runnervmvrwv9:10324] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6072e45330]
[runnervmvrwv9:10324] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6072e9eb2c]
[runnervmvrwv9:10324] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6072e4527e]
[runnervmvrwv9:10324] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6072e288ff]
[runnervmvrwv9:10324] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f60732a5ff5]
[runnervmvrwv9:10324] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f60732bb0da]
[runnervmvrwv9:10324] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f60732a5a55]
[runnervmvrwv9:10324] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f60732a5a6f]
[runnervmvrwv9:10324] [ 8] plumed(+0x146dd)[0x5647e8dde6dd]
[runnervmvrwv9:10324] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6072e2a1ca]
[runnervmvrwv9:10324] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6072e2a28b]
[runnervmvrwv9:10324] [11] plumed(+0x15365)[0x5647e8ddf365]
[runnervmvrwv9:10324] *** End of error message ***
</pre>
{% endraw %}
