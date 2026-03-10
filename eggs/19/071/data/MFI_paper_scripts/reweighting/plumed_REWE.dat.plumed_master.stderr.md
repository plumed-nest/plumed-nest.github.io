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
[runnervm0kj6c:12317] *** Process received signal ***
[runnervm0kj6c:12317] Signal: Aborted (6)
[runnervm0kj6c:12317] Signal code:  (-6)
[runnervm0kj6c:12317] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8c7fe45330]
[runnervm0kj6c:12317] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8c7fe9eb2c]
[runnervm0kj6c:12317] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8c7fe4527e]
[runnervm0kj6c:12317] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8c7fe288ff]
[runnervm0kj6c:12317] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8c802a5ff5]
[runnervm0kj6c:12317] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8c802bb0da]
[runnervm0kj6c:12317] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8c802a5a55]
[runnervm0kj6c:12317] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8c802a5a6f]
[runnervm0kj6c:12317] [ 8] plumed_master(+0x146dd)[0x55faf9d9a6dd]
[runnervm0kj6c:12317] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8c7fe2a1ca]
[runnervm0kj6c:12317] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8c7fe2a28b]
[runnervm0kj6c:12317] [11] plumed_master(+0x15365)[0x55faf9d9b365]
[runnervm0kj6c:12317] *** End of error message ***
</pre>
{% endraw %}
