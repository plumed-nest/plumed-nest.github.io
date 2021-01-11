**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_FB_rewe.dat   
(download [zipped raw stdout](plumed_FB_rewe.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Grid.cpp:575, function static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
+++ message follows +++
no column labelled metad.bias in in grid input
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f31d073d4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f31d073d428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f31d073f02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f31d0d7784d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f31d0d756b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f31d0d75701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f31d0d75919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f31d0728830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12354] *** End of error message ***
</pre>
{% endraw %}
