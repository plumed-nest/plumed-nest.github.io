**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
Download: [zipped raw stdout](plumed_REWE.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_REWE.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[runnervmw9dnm:11703] *** Process received signal ***
[runnervmw9dnm:11703] Signal: Aborted (6)
[runnervmw9dnm:11703] Signal code:  (-6)
[runnervmw9dnm:11703] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1f83445330]
[runnervmw9dnm:11703] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1f8349eb2c]
[runnervmw9dnm:11703] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1f8344527e]
[runnervmw9dnm:11703] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1f834288ff]
[runnervmw9dnm:11703] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1f838a5ff5]
[runnervmw9dnm:11703] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1f838bb0da]
[runnervmw9dnm:11703] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1f838a5a55]
[runnervmw9dnm:11703] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1f838a5a6f]
[runnervmw9dnm:11703] [ 8] plumed(+0x146dd)[0x5623462e56dd]
[runnervmw9dnm:11703] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1f8342a1ca]
[runnervmw9dnm:11703] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1f8342a28b]
[runnervmw9dnm:11703] [11] plumed(+0x15365)[0x5623462e6365]
[runnervmw9dnm:11703] *** End of error message ***
</pre>
{% endraw %}
