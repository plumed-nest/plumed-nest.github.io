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
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID, REWEIGHTING_NHILLS
[runnervmw9dnm:11719] *** Process received signal ***
[runnervmw9dnm:11719] Signal: Aborted (6)
[runnervmw9dnm:11719] Signal code:  (-6)
[runnervmw9dnm:11719] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7ed7845330]
[runnervmw9dnm:11719] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7ed789eb2c]
[runnervmw9dnm:11719] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7ed784527e]
[runnervmw9dnm:11719] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7ed78288ff]
[runnervmw9dnm:11719] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7ed7ca5ff5]
[runnervmw9dnm:11719] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7ed7cbb0da]
[runnervmw9dnm:11719] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7ed7ca5a55]
[runnervmw9dnm:11719] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7ed7ca5a6f]
[runnervmw9dnm:11719] [ 8] plumed_master(+0x146dd)[0x562542d396dd]
[runnervmw9dnm:11719] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7ed782a1ca]
[runnervmw9dnm:11719] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7ed782a28b]
[runnervmw9dnm:11719] [11] plumed_master(+0x15365)[0x562542d3a365]
[runnervmw9dnm:11719] *** End of error message ***
</pre>
{% endraw %}
