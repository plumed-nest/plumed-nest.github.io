**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_FB_rewe.dat   
Download: [zipped raw stdout](plumed_FB_rewe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_FB_rewe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled metad.bias in in grid input
[runnervm0kj6c:12266] *** Process received signal ***
[runnervm0kj6c:12266] Signal: Aborted (6)
[runnervm0kj6c:12266] Signal code:  (-6)
[runnervm0kj6c:12266] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff1b9645330]
[runnervm0kj6c:12266] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff1b969eb2c]
[runnervm0kj6c:12266] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff1b964527e]
[runnervm0kj6c:12266] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff1b96288ff]
[runnervm0kj6c:12266] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff1b9aa5ff5]
[runnervm0kj6c:12266] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff1b9abb0da]
[runnervm0kj6c:12266] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff1b9aa5a55]
[runnervm0kj6c:12266] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff1b9aa5a6f]
[runnervm0kj6c:12266] [ 8] plumed_master(+0x146dd)[0x557c00fa86dd]
[runnervm0kj6c:12266] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff1b962a1ca]
[runnervm0kj6c:12266] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff1b962a28b]
[runnervm0kj6c:12266] [11] plumed_master(+0x15365)[0x557c00fa9365]
[runnervm0kj6c:12266] *** End of error message ***
</pre>
{% endraw %}
