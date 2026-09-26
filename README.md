This cover letter and resume is great for people or students with thin resumes. This example is a one page cover letter and a one page resume. Compile BOTH the resume and the cover separately, so that each files dates are the same, even if you make no changes to one or the other. Then when you compile the resume, the cover is automatically included as the default in the cv.tex file with the same date as the resume, and the page numbers are automatically adjusted as needed. If you require only the cv.tex file, then you can simply % out the cover letter command, which is the first line of text after \begin{document}: 

\includepdf[pages={1}]{studentcv (cover).pdf} % adds the Cover

% \includepdf[pages={1}]{studentcv (cover).pdf} % eliminates the Cover

