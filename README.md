CSSMatrix
=========

A <code>WebkitCSSMatrix</code> and <code>MSCSSMatrix</code> polyfill for older browsers and browsers (specifically Firefox and Opera) without current support for this feature.

The <code>CSSMatrix</code> object represent a 4x4 homogeneous matrix for 3D transforms.  The development target is to mirror the functionality provided by the native <code>WebkitCSSMatrix</code> object.  Towards that goal, the only function remaining unimplemented is <code>rotate()</code>. (To match <code>MSCSSMatrix</code>, the function <code>multiplyLeft()</code> will need to be implemented as well).


A few links for you...

<a href="http://msdn.microsoft.com/en-us/library/windows/apps/hh453593.aspx">MSDN description of MSCSSMatrix</a>

<a href="https://developer.apple.com/library/safari/documentation/AudioVideo/Reference/WebKitCSSMatrixClassReference/WebKitCSSMatrix/WebKitCSSMatrix.html">SDL description of WebkitCSSMatrix</a> 

<a href="http://www.w3.org/TR/css3-transforms/#cssmatrix-interface">W3C specification for 2D Transformations</a>

<a href="http://www.w3.org/TR/css3-3d-transforms/#cssmatrix-interface">W3C specification for 3D Transformations</a>


Nota Bene : functions encapsulated by double dashes, i.e. <code>\_\_functionName\_\_</code> are utility functions designed to optimize the matrix's calculations, but which do not appear in either the WebkitCSSMatrix or the MSCSSMatrix spec.


