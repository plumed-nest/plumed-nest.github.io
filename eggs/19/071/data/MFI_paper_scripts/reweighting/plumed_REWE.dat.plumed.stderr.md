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
[runnervm0kj6c:12302] *** Process received signal ***
[runnervm0kj6c:12302] Signal: Aborted (6)
[runnervm0kj6c:12302] Signal code:  (-6)
[runnervm0kj6c:12302] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa253845330]
[runnervm0kj6c:12302] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa25389eb2c]
[runnervm0kj6c:12302] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa25384527e]
[runnervm0kj6c:12302] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa2538288ff]
[runnervm0kj6c:12302] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa253ca5ff5]
[runnervm0kj6c:12302] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa253cbb0da]
[runnervm0kj6c:12302] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa253ca5a55]
[runnervm0kj6c:12302] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa253ca5a6f]
[runnervm0kj6c:12302] [ 8] plumed(+0x146dd)[0x55cb9ce686dd]
[runnervm0kj6c:12302] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa25382a1ca]
[runnervm0kj6c:12302] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa25382a28b]
[runnervm0kj6c:12302] [11] plumed(+0x15365)[0x55cb9ce69365]
[runnervm0kj6c:12302] *** End of error message ***
</pre>
{% endraw %}
