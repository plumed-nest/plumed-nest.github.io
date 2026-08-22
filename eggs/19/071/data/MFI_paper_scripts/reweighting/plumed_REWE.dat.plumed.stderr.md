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
[runnervm76f27:11231] *** Process received signal ***
[runnervm76f27:11231] Signal: Aborted (6)
[runnervm76f27:11231] Signal code:  (-6)
[runnervm76f27:11231] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f488b845330]
[runnervm76f27:11231] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f488b89ec0c]
[runnervm76f27:11231] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f488b84527e]
[runnervm76f27:11231] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f488b8288ff]
[runnervm76f27:11231] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f488bca5ff5]
[runnervm76f27:11231] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f488bcbb0da]
[runnervm76f27:11231] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f488bca5a55]
[runnervm76f27:11231] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f488bca5a6f]
[runnervm76f27:11231] [ 8] plumed(+0x146dd)[0x560475d026dd]
[runnervm76f27:11231] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f488b82a1ca]
[runnervm76f27:11231] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f488b82a28b]
[runnervm76f27:11231] [11] plumed(+0x15365)[0x560475d03365]
[runnervm76f27:11231] *** End of error message ***
</pre>
{% endraw %}
