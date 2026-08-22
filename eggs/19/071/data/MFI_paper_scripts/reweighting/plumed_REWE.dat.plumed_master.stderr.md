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
[runnervm76f27:11247] *** Process received signal ***
[runnervm76f27:11247] Signal: Aborted (6)
[runnervm76f27:11247] Signal code:  (-6)
[runnervm76f27:11247] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd5abc45330]
[runnervm76f27:11247] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd5abc9ec0c]
[runnervm76f27:11247] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd5abc4527e]
[runnervm76f27:11247] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd5abc288ff]
[runnervm76f27:11247] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd5ac0a5ff5]
[runnervm76f27:11247] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd5ac0bb0da]
[runnervm76f27:11247] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd5ac0a5a55]
[runnervm76f27:11247] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd5ac0a5a6f]
[runnervm76f27:11247] [ 8] plumed_master(+0x146dd)[0x5583172836dd]
[runnervm76f27:11247] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd5abc2a1ca]
[runnervm76f27:11247] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd5abc2a28b]
[runnervm76f27:11247] [11] plumed_master(+0x15365)[0x558317284365]
[runnervm76f27:11247] *** End of error message ***
</pre>
{% endraw %}
