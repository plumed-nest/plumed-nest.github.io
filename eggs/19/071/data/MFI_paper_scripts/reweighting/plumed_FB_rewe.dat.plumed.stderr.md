**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_FB_rewe.dat   
Download: [zipped raw stdout](plumed_FB_rewe.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FB_rewe.dat.plumed.stderr.txt.zip) 
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
[runnervm0kj6c:12250] *** Process received signal ***
[runnervm0kj6c:12250] Signal: Aborted (6)
[runnervm0kj6c:12250] Signal code:  (-6)
[runnervm0kj6c:12250] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2a7ea45330]
[runnervm0kj6c:12250] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2a7ea9eb2c]
[runnervm0kj6c:12250] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2a7ea4527e]
[runnervm0kj6c:12250] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2a7ea288ff]
[runnervm0kj6c:12250] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2a7eea5ff5]
[runnervm0kj6c:12250] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2a7eebb0da]
[runnervm0kj6c:12250] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2a7eea5a55]
[runnervm0kj6c:12250] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2a7eea5a6f]
[runnervm0kj6c:12250] [ 8] plumed(+0x146dd)[0x5560a4d0c6dd]
[runnervm0kj6c:12250] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2a7ea2a1ca]
[runnervm0kj6c:12250] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2a7ea2a28b]
[runnervm0kj6c:12250] [11] plumed(+0x15365)[0x5560a4d0d365]
[runnervm0kj6c:12250] *** End of error message ***
</pre>
{% endraw %}
