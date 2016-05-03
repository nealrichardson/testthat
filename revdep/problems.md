# Setup

## Platform

|setting  |value                        |
|:--------|:----------------------------|
|version  |R version 3.2.4 (2016-03-10) |
|system   |x86_64, darwin13.4.0         |
|ui       |X11                          |
|language |(EN)                         |
|collate  |en_US.UTF-8                  |
|tz       |America/Chicago              |
|date     |2016-04-18                   |

## Packages

|package  |*  |version |date       |source                  |
|:--------|:--|:-------|:----------|:-----------------------|
|covr     |   |2.0.1   |2016-04-06 |CRAN (R 3.2.4)          |
|crayon   |   |1.3.1   |2015-07-13 |CRAN (R 3.2.0)          |
|devtools |*  |1.11.0  |2016-04-12 |CRAN (R 3.2.4)          |
|digest   |   |0.6.9   |2016-01-08 |CRAN (R 3.2.3)          |
|magrittr |   |1.5     |2014-11-22 |CRAN (R 3.2.0)          |
|praise   |   |1.0.0   |2015-08-11 |CRAN (R 3.2.0)          |
|R6       |   |2.1.2   |2016-01-26 |CRAN (R 3.2.3)          |
|testthat |*  |1.0.1   |2016-04-18 |local (hadley/testthat) |
|withr    |   |1.0.1   |2016-02-04 |CRAN (R 3.2.3)          |

# Check results
125 packages with problems

## afex (0.16-1)
Maintainer: Henrik Singmann <singmann+afex@gmail.com>

0 errors | 1 warning  | 0 notes

```
checking whether package ‘afex’ can be installed ... WARNING
Found the following significant warnings:
  Warning: package ‘lme4’ was built under R version 3.2.5
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/afex.Rcheck/00install.out’ for details.
```

## aLFQ (1.3.3)
Maintainer: George Rosenberger <rosenberger@imsb.biol.ethz.ch>

1 error  | 0 warnings | 0 notes

```
checking whether package ‘aLFQ’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/aLFQ.Rcheck/00install.out’ for details.
```

## backShift (0.1.3)
Maintainer: Christina Heinze <heinze@stat.math.ethz.ch>  
Bug reports: https://github.com/christinaheinze/backShift/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘backShift’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/backShift.Rcheck/00install.out’ for details.
```

## BayesFactor (0.9.12-2)
Maintainer: Richard D. Morey <richarddmorey@gmail.com>  
Bug reports: https://github.com/richarddmorey/BayesFactor/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## BBmisc (1.9)
Maintainer: Bernd Bischl <bernd_bischl@gmx.net>  
Bug reports: https://github.com/berndbischl/BBmisc/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/run-all.R’ failed.
Last 13 lines of output:
  1. Failure: makeProgressBar global options (@test_makeProgressBar.R#41) 
  2. Failure: makeProgressBar global options (@test_makeProgressBar.R#41) 
  3. Failure: makeProgressBar global options (@test_makeProgressBar.R#41) 
  4. Failure: makeProgressBar global options (@test_makeProgressBar.R#41) 
  5. Failure: makeProgressBar global options (@test_makeProgressBar.R#41) 
  6. Failure: makeProgressBar global options (@test_makeProgressBar.R#41) 
  7. Failure: suppressAll (@test_suppressAll.R#6) 
  8. Failure: suppressAll (@test_suppressAll.R#7) 
  9. Failure: suppressAll (@test_suppressAll.R#7) 
  1. ...
  
  Error: testthat unit tests failed
  Execution halted
```

## biom (0.3.12)
Maintainer: Paul J. McMurdie <mcmurdie@stanford.edu>  
Bug reports: https://github.com/joey711/biom/issues

1 error  | 0 warnings | 1 note 

```
checking tests ... ERROR
Running the tests in ‘tests/testthat-biom.R’ failed.
Last 13 lines of output:
  1. Failure: show method output tests (@test-IO.R#69) ---------------------------
  `x1` produced no output
  
  
  2. Failure: show method output tests (@test-IO.R#70) ---------------------------
  `x4` produced no output
  
  
  DONE ===========================================================================
  Error: Test failures
  In addition: Warning message:
  Placing tests in `inst/tests/` is deprecated. Please use `tests/testthat/` instead 
  Execution halted

checking DESCRIPTION meta-information ... NOTE
Malformed Title field: should not end in a period.
```

## biomartr (0.0.3)
Maintainer: Hajk-Georg Drost <hgd23@cam.ac.uk>  
Bug reports: https://github.com/HajkD/biomartr/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Packages required but not available: ‘biomaRt’ ‘Biostrings’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## blackbox (1.0)
Maintainer: François Rousset <francois.rousset@umontpellier.fr>

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## blme (1.0-4)
Maintainer: Vincent Dorie <vjd4@nyu.edu>  
Bug reports: https://github.com/vdorie/blme/issues

0 errors | 1 warning  | 0 notes

```
checking whether package ‘blme’ can be installed ... WARNING
Found the following significant warnings:
  Warning: package ‘lme4’ was built under R version 3.2.5
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/blme.Rcheck/00install.out’ for details.
```

## bnclassify (0.3.2)
Maintainer: Mihaljevic Bojan <bmihaljevic@fi.upm.es>  
Bug reports: http://github.com/bmihaljevic/bnclassify/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Packages required but not available: ‘graph’ ‘RBGL’

Package suggested but not available for checking: ‘Rgraphviz’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## boral (0.9.1)
Maintainer: Francis Hui <fhui28@gmail.com>

1 error  | 0 warnings | 0 notes

```
checking whether package ‘boral’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/boral.Rcheck/00install.out’ for details.
```

## brms (0.8.0)
Maintainer: Paul-Christian Buerkner <paul.buerkner@gmail.com>  
Bug reports: http://github.com/paul-buerkner/brms/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘brms’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/brms.Rcheck/00install.out’ for details.
```

## Causata (4.2-0)
Maintainer: Justin Hemann <justinh@causata.com>

0 errors | 1 warning  | 5 notes

```
checking whether package ‘Causata’ can be installed ... WARNING
Found the following significant warnings:
  Warning: package ‘R.utils’ was built under R version 3.2.5
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/Causata.Rcheck/00install.out’ for details.

checking DESCRIPTION meta-information ... NOTE
Malformed Title field: should not end in a period.

checking top-level files ... NOTE
Non-standard file/directory found at top level:
  ‘integration_tests’

checking R code for possible problems ... NOTE
GetMetadata.Connect: no visible global function definition for
  ‘dbGetQuery’
GetRawData.Connect: no visible global function definition for
  ‘dbGetQuery’

checking line endings in Makefiles ... NOTE
Found the following Makefile(s) without a final LF:
  inst/doc/Makefile
Some ‘make’ programs ignore lines not ending in LF.

checking files in ‘vignettes’ ... NOTE
The following files look like leftovers/mistakes:
  ‘Causata-vignette.log’
Please remove them from your package.
The following directory looks like a leftover from 'knitr':
  ‘figure’
Please remove from your package.
```

## cellranger (1.0.0)
Maintainer: Jennifer Bryan <jenny@stat.ubc.ca>  
Bug reports: https://github.com/jennybc/cellranger/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  > library(cellranger)
  > 
  > test_check("cellranger")
  1. Failure: Print method works (@test-cell-specification.R#163) ----------------
  cell_limits(c(NA, 7), c(3, NA)) produced no output
  
  
  testthat results ================================================================
  OK: 93 SKIPPED: 0 FAILED: 1
  1. Failure: Print method works (@test-cell-specification.R#163) 
  
  Error: testthat unit tests failed
  Execution halted
```

## cleangeo (0.1-1)
Maintainer: Emmanuel Blondel <emmanuel.blondel1@gmail.com>  
Bug reports: https://github.com/eblondel/cleangeo/issues

0 errors | 1 warning  | 0 notes

```
checking whether package ‘cleangeo’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import ‘sp::nowrapSpatialLines’ by ‘maptools::nowrapSpatialLines’ when loading ‘cleangeo’
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/cleangeo.Rcheck/00install.out’ for details.
```

## cocor (1.1-2)
Maintainer: Birk Diedenhofen <mail@birkdiedenhofen.de>

1 error  | 0 warnings | 1 note 

```
checking tests ... ERROR
Running the tests in ‘tests/test.cocor.package.R’ failed.
Last 13 lines of output:
  10. Failure: Output is correct (@test.r#101) -----------------------------------
  cocor.indep.groups(...) produced no output
  
  
  11. Failure: Output is correct (@test.r#102) -----------------------------------
  cocor.indep.groups(...) produced no output
  
  
  DONE ===========================================================================
  Error: Test failures
  In addition: Warning message:
  Placing tests in `inst/tests/` is deprecated. Please use `tests/testthat/` instead 
  Execution halted

checking package dependencies ... NOTE
Package which this enhances but not available for checking: ‘rkward’
```

## CompareCausalNetworks (0.1.4)
Maintainer: Christina Heinze <heinze@stat.math.ethz.ch>  
Bug reports: 
        https://github.com/christinaheinze/CompareCausalNetworks/issues

2 errors | 0 warnings | 0 notes

```
checking examples ... ERROR
Running examples in ‘CompareCausalNetworks-Ex.R’ failed
The error most likely occurred in:

> base::assign(".ptime", proc.time(), pos = "CheckExEnv")
> ### Name: getParents
> ### Title: Estimate the connectivity matrix of a causal graph
> ### Aliases: getParents
> ### Keywords: Causality, Graph estimations
> 
> ### ** Examples
> 
> ## load the backShift package for data generation and plotting functionality
> if(!requireNamespace("backShift", quietly = TRUE))
+  stop("The package 'backShift' is needed for the examples to
+  work. Please install it.", call. = FALSE)
Error: The package 'backShift' is needed for the examples to
 work. Please install it.
Execution halted

checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  6: missingDependenciesMessage("pcalg", method)
  7: stop(paste("The package '", package, "' is needed for ", method, " to \nwork. Please install it.", 
         sep = ""), call. = FALSE)
  
  testthat results ================================================================
  OK: 12 SKIPPED: 0 FAILED: 4
  1. Error: Checks output type for pc (@test_getParents_defaults_all_methods.R#19) 
  2. Error: Checks output type for LINGAM (@test_getParents_defaults_all_methods.R#19) 
  3. Error: Checks output type for ges (@test_getParents_defaults_all_methods.R#19) 
  4. Error: Checks output type for rfci (@test_getParents_defaults_all_methods.R#19) 
  
  Error: testthat unit tests failed
  Execution halted
```

## datapack (1.0.0)
Maintainer: Matthew B. Jones <jones@nceas.ucsb.edu>  
Bug reports: https://github.com/ropensci/datapack/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘datapack’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/datapack.Rcheck/00install.out’ for details.
```

## ddpcr (1.1.2)
Maintainer: Dean Attali <daattali@gmail.com>  
Bug reports: https://github.com/daattali/ddpcr/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  
  
  2. Failure: quiet works (@test-utils.R#55) -------------------------------------
  quiet(cat("hello world")) produced no output
  
  
  testthat results ================================================================
  OK: 268 SKIPPED: 0 FAILED: 2
  1. Failure: quiet works (@test-utils.R#54) 
  2. Failure: quiet works (@test-utils.R#55) 
  
  Error: testthat unit tests failed
  Execution halted
```

## describer (0.2.0)
Maintainer: Paul Hendricks <paul.hendricks.2013@owu.edu>  
Bug reports: https://github.com/paulhendricks/describer/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
    expect_equal(hello(), 'Hello World')    
                                        ^~~~
  tests/testthat/test_dir/test-helper.R:7:1: style: Trailing blank lines are superfluous.
  
  ^
  
  
  testthat results ================================================================
  OK: 9 SKIPPED: 0 FAILED: 1
  1. Failure: Package Style (@test-styling.R#4) 
  
  Error: testthat unit tests failed
  Execution halted
```

## Dowd (0.12)
Maintainer: Dinesh Acharya <dines.acharya@gmail.com>

0 errors | 1 warning  | 0 notes

```
checking whether package ‘Dowd’ can be installed ... WARNING
Found the following significant warnings:
  Warning: package ‘forecast’ was built under R version 3.2.5
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/Dowd.Rcheck/00install.out’ for details.
```

## DSsim (1.0.4)
Maintainer: Laura Marshall <lhm@st-and.ac.uk>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/run-all.R’ failed.
Last 13 lines of output:
  Actual value: "invalid class "Region" object: The lengths of the coords and gaps lists differ, these must be the same and equal to the number of strata."
  
  
  2. Failure: Can create object or return correct error messages (@test_Constructors.R#16) 
  error$message does not match "You must provide either coordinates or a shapefile.".
  Actual value: "You must provide either coordinates or a shapefile"
  
  
  DONE ===========================================================================
  Error: Test failures
  In addition: Warning message:
  Placing tests in `inst/tests/` is deprecated. Please use `tests/testthat/` instead 
  Execution halted
```

## eggCounts (1.0)
Maintainer: Craig Wang <craig.wang@uzh.ch>

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Packages required but not available: ‘StanHeaders’ ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## falsy (1.0.1)
Maintainer: Gabor Csardi <csardi.gabor@gmail.com>  
Bug reports: https://github.com/gaborcsardi/falsy/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  > library(falsy)
  > 
  > test_check("falsy")
  1. Failure: try_quietly works (@test_falsy.R#126) ------------------------------
  try_quietly(stop("foo!")) produced no output
  
  
  testthat results ================================================================
  OK: 46 SKIPPED: 0 FAILED: 1
  1. Failure: try_quietly works (@test_falsy.R#126) 
  
  Error: testthat unit tests failed
  Execution halted
```

## forecastHybrid (0.1.5)
Maintainer: David Shaub <davidshaub@gmx.com>  
Bug reports: https://github.com/ellisp/forecastHybrid/issues

0 errors | 1 warning  | 0 notes

```
checking whether package ‘forecastHybrid’ can be installed ... WARNING
Found the following significant warnings:
  Warning: package ‘forecast’ was built under R version 3.2.5
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/forecastHybrid.Rcheck/00install.out’ for details.
```

## FunChisq (2.2.3)
Maintainer: Joe Song <joemsong@cs.nmsu.edu>

0 errors | 1 warning  | 0 notes

```
checking whether package ‘FunChisq’ can be installed ... WARNING
Found the following significant warnings:
  /usr/local/include/boost/math/special_functions/detail/lanczos_sse2.hpp:54:4: warning: 'register' storage class specifier is deprecated [-Wdeprecated-register]
  /usr/local/include/boost/math/special_functions/detail/lanczos_sse2.hpp:55:4: warning: 'register' storage class specifier is deprecated [-Wdeprecated-register]
  /usr/local/include/boost/math/special_functions/detail/lanczos_sse2.hpp:56:4: warning: 'register' storage class specifier is deprecated [-Wdeprecated-register]
  /usr/local/include/boost/math/special_functions/detail/lanczos_sse2.hpp:57:4: warning: 'register' storage class specifier is deprecated [-Wdeprecated-register]
  /usr/local/include/boost/math/special_functions/detail/lanczos_sse2.hpp:58:4: warning: 'register' storage class specifier is deprecated [-Wdeprecated-register]
  /usr/local/include/boost/math/special_functions/detail/lanczos_sse2.hpp:139:4: warning: 'register' storage class specifier is deprecated [-Wdeprecated-register]
  /usr/local/include/boost/math/special_functions/detail/lanczos_sse2.hpp:140:4: warning: 'register' storage class specifier is deprecated [-Wdeprecated-register]
  /usr/local/include/boost/math/special_functions/detail/lanczos_sse2.hpp:141:4: warning: 'register' storage class specifier is deprecated [-Wdeprecated-register]
  /usr/local/include/boost/math/special_functions/detail/lanczos_sse2.hpp:142:4: warning: 'register' storage class specifier is deprecated [-Wdeprecated-register]
  /usr/local/include/boost/math/special_functions/detail/lanczos_sse2.hpp:143:4: warning: 'register' storage class specifier is deprecated [-Wdeprecated-register]
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/FunChisq.Rcheck/00install.out’ for details.
```

## futile.logger (1.4.1)
Maintainer: Brian Lee Yung Rowe <r@zatonovo.com>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  > library(testthat)
  > test_check("futile.logger")
  Loading required package: futile.logger
  1. Failure: lower levels are not logged (@test_debug.R#19) ---------------------
  flog.trace("testlog") produced no output
  
  
  testthat results ================================================================
  OK: 68 SKIPPED: 0 FAILED: 1
  1. Failure: lower levels are not logged (@test_debug.R#19) 
  
  Error: testthat unit tests failed
  Execution halted
```

## gemtc (0.8)
Maintainer: Gert van Valkenhoef <g.h.m.van.valkenhoef@rug.nl>

1 error  | 0 warnings | 0 notes

```
checking examples ... ERROR
Running examples in ‘gemtc-Ex.R’ failed
The error most likely occurred in:

> base::assign(".ptime", proc.time(), pos = "CheckExEnv")
> ### Name: mtc.hy.prior
> ### Title: Set priors for the heterogeneity parameter
> ### Aliases: mtc.hy.prior mtc.hy.empirical.lor
> 
> ### ** Examples
> 
> # NOTE: the mtc.run commands below are for illustrative purposes, such a small
> # number of iterations should obviously not be used in practice.
> 
> # set a uniform prior standard deviation
> model1 <- mtc.model(smoking, hy.prior=mtc.hy.prior("std.dev", "dunif", 0, 2))
> result <- mtc.run(model1, n.adapt=10, n.iter=10)
Error: .onLoad failed in loadNamespace() for 'rjags', details:
  call: dyn.load(file, DLLpath = DLLpath, ...)
  error: unable to load shared object '/Users/hadley/R-revdep/rjags/libs/rjags.so':
  dlopen(/Users/hadley/R-revdep/rjags/libs/rjags.so, 10): Library not loaded: /usr/local/lib/libjags.3.dylib
  Referenced from: /Users/hadley/R-revdep/rjags/libs/rjags.so
  Reason: image not found
Execution halted
```

## geojsonio (0.1.8)
Maintainer: Scott Chamberlain <myrmecocystus@gmail.com>  
Bug reports: http://www.github.com/ropensci/geojsonio/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/test-all.R’ failed.
Last 13 lines of output:
  5: val_fxn(x)
  6: POST(v_url(), body = upload_file(file))
  7: request_perform(req, hu$handle$handle)
  8: request_fetch(req$output, req$url, handle)
  9: request_fetch.write_memory(req$output, req$url, handle)
  10: curl::curl_fetch_memory(url, handle = handle)
  
  testthat results ================================================================
  OK: 288 SKIPPED: 22 FAILED: 1
  1. Error: validate works with SpatialGridDataFrame inputs (@test-validate.R#160) 
  
  Error: testthat unit tests failed
  Execution halted
```

## GetoptLong (0.1.2)
Maintainer: Zuguang Gu <z.gu@dkfz.de>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/test-all.R’ failed.
Last 13 lines of output:
  
  27. test `version` and `help` options (@test_GetoptLong.R#247) - cannot remove file '/tmp/RtmpqAUdMC/fileae967ce26d7e.json', reason 'No such file or directory'
  
  Failed -------------------------------------------------------------------------
  1. Failure: test `cat_prefix` (@test_qq.R#85) ----------------------------------
  qqcat("a") produced no output
  
  
  DONE ===========================================================================
  Error: Test failures
  In addition: Warning message:
  Placing tests in `inst/tests/` is deprecated. Please use `tests/testthat/` instead 
  Execution halted
```

## ggfortify (0.1.0)
Maintainer: Masaaki Horikoshi <sinhrks@gmail.com>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/test-all.R’ failed.
Last 13 lines of output:
  names(fortified) not equal to `expected_names`.
  Lengths differ: 6 vs 7
  
  
  Loading required package: urca
  Loading required package: lmtest
  testthat results ================================================================
  OK: 554 SKIPPED: 1 FAILED: 2
  1. Failure: fortify.cpt works for AirPassengers (@test-changepoint.R#24) 
  2. Failure: fortify.ets works for austres (@test-forecast.R#83) 
  
  Error: testthat unit tests failed
  Execution halted
```

## glmmsr (0.1.1)
Maintainer: Helen Ogden <heogden12@gmail.com>  
Bug reports: http://github.com/heogden/glmmsr/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## glycanr (0.3.0)
Maintainer: Ivo Ugrina <ivo@iugrina.com>  
Bug reports: https://github.com/iugrina/glycanr/issues

2 errors | 0 warnings | 1 note 

```
checking examples ... ERROR
Running examples in ‘glycanr-Ex.R’ failed
The error most likely occurred in:

> base::assign(".ptime", proc.time(), pos = "CheckExEnv")
> ### Name: quantilenorm
> ### Title: Quantile Normalization of glycan data
> ### Aliases: quantilenorm
> 
> ### ** Examples
> 
> data(mpiu)
> mpiun <- quantilenorm(mpiu)
Error in quantilenorm(mpiu) : 
  Unable to proceed since package preprocessCore from
        BioConductor is not available on this system. This
        package is a prerequisite to use the quantilenorm function!
Execution halted

checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  
  The following objects are masked from 'package:base':
  
      intersect, setdiff, setequal, union
  
  Error in quantilenorm(mpiu, transpose = TRUE) : 
    Unable to proceed since package preprocessCore from
          BioConductor is not available on this system. This
          package is a prerequisite to use the quantilenorm function!
  Calls: test_check ... force -> source_file -> eval -> eval -> quantilenorm
  testthat results ================================================================
  OK: 5 SKIPPED: 0 FAILED: 0
  Execution halted

checking package dependencies ... NOTE
Package suggested but not available for checking: ‘preprocessCore’
```

## Gmisc (1.3.1)
Maintainer: Max Gordon <max@gforge.se>  
Bug reports: https://github.com/gforge/Gmisc/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
   $ echo: logi TRUE
  
    ordinary text without R code
  
  output file: Full_test_suite.knit.md
  
  /usr/local/bin/pandoc +RTS -K512m -RTS Full_test_suite.utf8.md --to html --from markdown+autolink_bare_uris+ascii_identifiers+tex_math_single_backslash --output /tmp/Rtmpv4ksiL/tmp.html --smart --email-obfuscation none --standalone --section-divs --template /Users/hadley/R-revdep/rmarkdown/rmd/h/default.html --css docx.css --no-highlight 
  
  Output created: /tmp/Rtmpv4ksiL/tmp.html
  
   *** caught segfault ***
  address 0x0, cause 'unknown'
  aborting ...
```

## gpuR (1.1.2)
Maintainer: Charles Determan Jr. <cdetermanjr@gmail.com>  
Bug reports: http://github.com/cdeterman/gpuR/issues/new

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Packages required but not available: ‘RcppEigen’ ‘RViennaCL’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## gWidgets2RGtk2 (1.0-4)
Maintainer: John Verzani <jverzani@gmail.com>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/run-tests.R’ failed.
Last 13 lines of output:
  > 
  > sapply(f, function(i) {
  +   message("testing ", i)
  +   source(i)
  + })
  testing /Users/hadley/R-revdep/gWidgets2/tests/button.R
  Loading required package: gWidgets2RGtk2
  Loading required package: memoise
  Loading required package: RGtk2
  R session is headless; GTK+ not initialized.
  Error in guiToolkit() : Can't load RGtk2
  Calls: sapply ... withVisible -> eval -> eval -> gwindow -> guiToolkit
  Execution halted
```

## gWidgets2tcltk (1.0-4)
Maintainer: John Verzani <jverzani@gmail.com>

1 error  | 0 warnings | 0 notes

```
checking whether package ‘gWidgets2tcltk’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/gWidgets2tcltk.Rcheck/00install.out’ for details.
```

## h5 (0.9.5)
Maintainer: Mario Annau <mario.annau@gmail.com>  
Bug reports: https://github.com/mannau/h5/issues

1 error  | 0 warnings | 1 note 

```
checking whether package ‘h5’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/h5.Rcheck/00install.out’ for details.

checking package dependencies ... NOTE
Package suggested but not available for checking: ‘highlight’
```

## harvestr (0.6.0)
Maintainer: Andrew Redd <andrew.redd@hsc.utah.edu>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat-package.R’ failed.
Last 13 lines of output:
  'arg' must be NULL or a character vector
  1: expect_that(harvest(x, mean, time = T), has_time) at /Users/hadley/Documents/devtools/testthat/revdep/checks/harvestr.Rcheck/harvestr/tests/test-timing.R:74
  2: condition(object) at /Users/hadley/Documents/devtools/testthat/R/expect-that.R:22
  3: expectation(T, "") at /Users/hadley/Documents/devtools/testthat/revdep/checks/harvestr.Rcheck/harvestr/tests/test-timing.R:37
  4: match.arg(type, c("success", "failure", "error", "skip", "warning")) at /Users/hadley/Documents/devtools/testthat/R/expectation.R:15
  5: stop("'arg' must be NULL or a character vector")
  
  DONE ===========================================================================
  Error: Test failures
  In addition: Warning messages:
  1: Placing tests in `inst/tests/` is deprecated. Please use `tests/testthat/` instead 
  2: package 'MCMCpack' was built under R version 3.2.5 
  Execution halted
```

## hts (5.0)
Maintainer: Rob J Hyndman <Rob.Hyndman@monash.edu>  
Bug reports: https://github.com/robjhyndman/hts/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## hunspell (1.2)
Maintainer: Jeroen Ooms <jeroen.ooms@stat.ucla.edu>  
Bug reports: https://github.com/jeroenooms/hunspell/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘hunspell’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/hunspell.Rcheck/00install.out’ for details.
```

## HydeNet (0.10.3)
Maintainer: Benjamin Nutter <benjamin.nutter@gmail.com>  
Bug reports: https://github.com/nutterb/HydeNet/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘graph’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## identifyr (0.1.3)
Maintainer: George Miranda <georgemirandajr@gmail.com>  
Bug reports: https://github.com/georgemirandajr/identifyr/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  1. Failure: string is padding correctly when PB is present (@test_pbnum.R#8) 
  2. Failure: string is padding correctly when PB is present (@test_pbnum.R#11) 
  3. Failure: string is padding correctly when PB is present (@test_pbnum.R#14) 
  4. Failure: string is padding correctly when PB is present (@test_pbnum.R#15) 
  5. Failure: string is padding correctly when PB is present (@test_pbnum.R#16) 
  6. Failure: string is padding correctly when PB is present (@test_pbnum.R#17) 
  7. Failure: string is padding correctly when PB is present (@test_pbnum.R#18) 
  8. Failure: string is padding correctly when X is present (@test_xnum.R#8) 
  9. Failure: string is padding correctly when X is present (@test_xnum.R#11) 
  1. ...
  
  Error: testthat unit tests failed
  Execution halted
```

## iptools (0.4.0)
Maintainer: Bob Rudis <bob@rudis.net>  
Bug reports: https://github.com/hrbrmstr/iptools/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘iptools’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/iptools.Rcheck/00install.out’ for details.
```

## KFAS (1.2.2)
Maintainer: Jouni Helske <jouni.helske@jyu.fi>  
Bug reports: https://github.com/helske/KFAS/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘KFAS’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/KFAS.Rcheck/00install.out’ for details.
```

## lava (1.4.3)
Maintainer: Klaus K. Holst <kkho@biostat.ku.dk>

1 error  | 0 warnings | 1 note 

```
checking tests ... ERROR
Running the tests in ‘tests/test-all.R’ failed.
Last 13 lines of output:
  4: getNamespace(ns)
  5: tryCatch(loadNamespace(name), error = function(e) stop(e))
  6: tryCatchList(expr, classes, parentenv, handlers)
  7: tryCatchOne(expr, names, parentenv, handlers[[1L]])
  8: value[[3L]](cond)
  
  testthat results ================================================================
  OK: 245 SKIPPED: 0 FAILED: 2
  1. Error: Effects (@test-inference.R#27) 
  2. Error: Graph attributes (@test-model.R#82) 
  
  Error: testthat unit tests failed
  Execution halted

checking package dependencies ... NOTE
Packages suggested but not available for checking: ‘graph’ ‘Rgraphviz’
```

## lawn (0.1.6)
Maintainer: Scott Chamberlain <myrmecocystus@gmail.com>  
Bug reports: http://www.github.com/ropensci/lawn/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/test-all.R’ failed.
Last 13 lines of output:
  > test_check("lawn")
  Loading required package: lawn
  1. Failure: lawn_union fails correctly (@test-union.R#51) ----------------------
  error$message does not match "Error : ReferenceError: afa is not defined\n".
  Actual value: "ReferenceError: afa is not defined"
  
  
  testthat results ================================================================
  OK: 892 SKIPPED: 0 FAILED: 1
  1. Failure: lawn_union fails correctly (@test-union.R#51) 
  
  Error: testthat unit tests failed
  Execution halted
```

## letsR (2.4)
Maintainer: Bruno Vilela <brunovilelasilva@hotmail.com>  
Bug reports: https://github.com/macroecology/letsR/issues

0 errors | 1 warning  | 0 notes

```
checking whether package ‘letsR’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import ‘maptools::nowrapSpatialLines’ by ‘sp::nowrapSpatialLines’ when loading ‘letsR’
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/letsR.Rcheck/00install.out’ for details.
```

## lfstat (0.8.0)
Maintainer: Tobias Gauster <t.gauster@boku.ac.at>

2 errors | 0 warnings | 0 notes

```
checking examples ... ERROR
Running examples in ‘lfstat-Ex.R’ failed
The error most likely occurred in:

> base::assign(".ptime", proc.time(), pos = "CheckExEnv")
> ### Name: tyears
> ### Title: Calculate Low-Flow Quantiles for given Return Periods
> ### Aliases: tyears
> ### Keywords: low-flow fitting
> 
... 73 lines ...
> 
> # applying a moving average before fitting
> ng2 <- ng
> ng2$flow <- ma(ng2$flow, n = 4)
> tyears(ng2, dist = c("gum", "wei", "ln3", "pe3"), event = rp,
+        plot = FALSE)
Warning in FUN(X[[i]], ...) :
  no non-missing arguments to min; returning Inf
Error in samlmu(xx) : NA/NaN/Inf in foreign function call (arg 1)
Calls: tyears -> evfit -> samlmu -> .Fortran
Execution halted

checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  1. Failure: water_year() interprets the origin argument correctly (@test-utils.R#11) 
  2. Failure: water_year() interprets the origin argument correctly (@test-utils.R#15) 
  3. Failure: water_year() interprets the origin argument correctly (@test-utils.R#19) 
  4. Failure: water_year() interprets the origin argument correctly (@test-utils.R#21) 
  5. Failure: water_year() interprets the origin argument correctly (@test-utils.R#25) 
  6. Failure: water_year() interprets the origin argument correctly (@test-utils.R#27) 
  7. Failure: water_year() interprets the assign argument correctly (@test-utils.R#33) 
  8. Failure: water_year() interprets the assign argument correctly (@test-utils.R#35) 
  9. Failure: water_year() interprets the assign argument correctly (@test-utils.R#38) 
  1. ...
  
  Error: testthat unit tests failed
  Execution halted
```

## lme4 (1.1-12)
Maintainer: Ben Bolker <bbolker+lme4@gmail.com>  
Bug reports: https://github.com/lme4/lme4/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## merTools (0.2.1)
Maintainer: Jared E. Knowles <jknowles@gmail.com>  
Bug reports: https://www.github.com/jknowles/merTools

0 errors | 1 warning  | 0 notes

```
checking whether package ‘merTools’ can be installed ... WARNING
Found the following significant warnings:
  Warning: package ‘lme4’ was built under R version 3.2.5
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/merTools.Rcheck/00install.out’ for details.
```

## mlr (2.8)
Maintainer: Bernd Bischl <bernd_bischl@gmx.net>  
Bug reports: https://github.com/mlr-org/mlr/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/run-base.R’ failed.
Last 13 lines of output:
  
  testthat results ================================================================
  OK: 2008 SKIPPED: 1 FAILED: 7
  1. Failure: chains (@test_base_chains.R#11) 
  2. Error: generateCalibrationData (@test_base_generateCalibration.R#14) 
  3. Error: generateLearningCurve (@test_base_generateLearningCurve.R#11) 
  4. Error: generatePartialPredictionData (@test_base_generatePartialPrediction.R#21) 
  5. Error: generateThreshVsPerfData (@test_base_generateThreshVsPerf.R#12) 
  6. Failure: getParamSet (@test_base_getParamSet.R#16) 
  7. Error: BenchmarkResult (@test_base_plotBMRBoxplots.R#12) 
  
  Error: testthat unit tests failed
  Execution halted
```

## mmand (1.3.0)
Maintainer: Jon Clayden <code@clayden.org>  
Bug reports: https://github.com/jonclayden/mmand/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## morse (2.1.1)
Maintainer: Philippe Ruiz <philippe.ruiz@univ-lyon1.fr>

1 error  | 0 warnings | 0 notes

```
checking whether package ‘morse’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/morse.Rcheck/00install.out’ for details.
```

## move (1.6.541)
Maintainer: Bart Kranstauber <bart.kranstauber@uni-konstanz.de>

1 error  | 0 warnings | 0 notes

```
checking whether package ‘move’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/move.Rcheck/00install.out’ for details.
```

## MRMR (0.1.3)
Maintainer: Brian A. Fannin <BFannin@RedwoodsGroup.com>

1 error  | 0 warnings | 2 notes

```
checking examples ... ERROR
Running examples in ‘MRMR-Ex.R’ failed
The error most likely occurred in:

> base::assign(".ptime", proc.time(), pos = "CheckExEnv")
> ### Name: CreateDevelopmentLags
> ### Title: Create triangle development lags
> ### Aliases: CreateDevelopmentLags
> 
> ### ** Examples
... 16 lines ...
> DevelopmentLags
[1] "12m 0d 0H 0M 0S" "24m 0d 0H 0M 0S" "12m 0d 0H 0M 0S"
> 
> # Case 3
> OriginStart = c(mdy("1/1/2000"), mdy("1/1/2000"), mdy("1/1/2001"))
> OriginEnd = c(mdy("12/31/2000"), mdy("12/31/2000"), mdy("12/31/2001"))
> OriginPeriods = CreateOriginPeriods(OriginStart, OriginEnd)
Error in OriginPeriodFromDates(OriginStart, OriginEnd) : 
  OriginStart and OriginEnd were supplied, but OriginStart is not a POSIXct or POSIXt class variable.
Calls: CreateOriginPeriods -> OriginPeriodFromDates
Execution halted

checking DESCRIPTION meta-information ... NOTE
Malformed Description field: should contain one or more complete sentences.

checking R code for possible problems ... NOTE
PlotResiduals: no visible global function definition for ‘.’
```

## MultiGHQuad (1.0)
Maintainer: Karel Kroeze <k.a.kroeze@utwente.nl>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  > 
  > test_check("MultiGHQuad")
  1. Error: Sum of weights is 1, pruning does not take too much (@test_generate_quadpoints.R#36) 
  unused argument (info = "q 2 ip 6")
  1: expect_less_than(1 - sum(not.pruned), 0.01, info = paste("q", q, "ip", ip)) at testthat/test_generate_quadpoints.R:36
  2: expect_lt(...) at /Users/hadley/Documents/devtools/testthat/R/expect-comparison.R:81
  
  testthat results ================================================================
  OK: 66 SKIPPED: 0 FAILED: 1
  1. Error: Sum of weights is 1, pruning does not take too much (@test_generate_quadpoints.R#36) 
  
  Error: testthat unit tests failed
  Execution halted
```

## multitable (1.6)
Maintainer: Steve C Walker <steve.walker@utoronto.ca>

1 error  | 0 warnings | 1 note 

```
checking running R code from vignettes ... ERROR
Errors in running code in vignettes:
when running code in ‘multitable.Rnw’
  ...
> p <- p + geom_point(aes(x = width, y = abundance, 
+     shape = life.history))

> p <- p + stat_smooth(aes(x = width, y = abundance), 
+     se = FALSE, method = "bayesglm", family = poisson, form = y ~ 
+         x + I(x^2), colo .... [TRUNCATED] 

  When sourcing ‘multitable.R’:
Error: Unknown parameters: family, form
Execution halted


checking re-building of vignette outputs ... NOTE
Error in re-building vignettes:
  ...
The following object is masked from ‘package:arm’:

    rescale

dimids automatically generated
dimids automatically generated
omitting width because it is not replicated along MARGIN
... 8 lines ...

omitting life.history because of the following error:
 Error in median.default(newX[, i], ...) : need numeric data

omitting trophic because it is not replicated along MARGIN
omitting life.history because it is not replicated along MARGIN

Error: processing vignette 'multitable.Rnw' failed with diagnostics:
 chunk 57 (label = a faceted ggplot scatterplot from a data list) 
Error : Unknown parameters: family, form
Execution halted
```

## mvtboost (0.4.1)
Maintainer: Patrick Miller <patrick.mil10@gmail.com>  
Bug reports: https://github.com/patr1ckm/mvtboost/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  
  Type 'demo()' for some demos, 'help()' for on-line help, or
  'help.start()' for an HTML browser interface to help.
  Type 'q()' to quit R.
  
  > library(testthat)
  > library(mvtboost)
  > 
  > test_check("mvtboost")
  Error: mvtb.covex(out) produced no output
  testthat results ================================================================
  OK: 72 SKIPPED: 0 FAILED: 0
  Execution halted
```

## mwaved (1.1.4)
Maintainer: Justin Rory Wishart <justin.wishart@mq.edu.au>  
Bug reports: https://github.com/jrwishart/mwaved/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘mwaved’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/mwaved.Rcheck/00install.out’ for details.
```

## myTAI (0.3.0)
Maintainer: Hajk-Georg Drost <hajk-georg.drost@informatik.uni-halle.de>  
Bug reports: https://github.com/HajkD/myTAI/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘edgeR’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## nabor (0.4.6)
Maintainer: Gregory Jefferis <jefferis@gmail.com>  
Bug reports: https://github.com/jefferis/nabor/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## nat (1.8.1)
Maintainer: Greg Jefferis <jefferis@gmail.com>  
Bug reports: https://github.com/jefferis/nat/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/test-all.R’ failed.
Last 13 lines of output:
    adding: DL3/EBH20L.swc (deflated 54%)
    adding: DL3/EBI22R.swc (deflated 53%)
  1. Failure: write.nrrd.header.for.file (@test-nrrd-io.R#132) -------------------
  error$message does not match "read.im3d".
  Actual value: "Unable to read data saved in format: am"
  
  
  testthat results ================================================================
  OK: 726 SKIPPED: 0 FAILED: 1
  1. Failure: write.nrrd.header.for.file (@test-nrrd-io.R#132) 
  
  Error: testthat unit tests failed
  Execution halted
```

## netdiffuseR (1.16.2)
Maintainer: George Vega Yon <g.vegayon@gmail.com>  
Bug reports: https://github.com/USCCANA/netdiffuseR/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  6. Failure: Length of inputs in edgelist_adjmat should match (detecting error) - edgelist data.frame (@test-adjmat.R#31) 
  7. Failure: Changing toa (@test-diffnet-class.R#36) 
  8. Failure: Changing toa (@test-diffnet-class.R#40) 
  9. Failure: diffnet print and summary (@test-diffnet-methods.R#111) 
  1. ...
  
  Error: testthat unit tests failed
  In addition: Warning messages:
  1: In as_diffnet(graph, times) : Coercing -toa- into integer.
  2: In as_diffnet(listgraph, toa) : Coercing -toa- into integer.
  3: In as_diffnet(listgraph, toa) : Coercing -toa- into integer.
  4: In as_diffnet(dyngraph, c(1, 1, 3, 2)) : Coercing -toa- into integer.
  Execution halted
```

## NlsyLinks (2.0.1)
Maintainer: Will Beasley <wibeasley@hotmail.com>  
Bug reports: https://github.com/LiveOak/NlsyLinks/issues

1 error  | 0 warnings | 1 note 

```
checking tests ... ERROR
Running the tests in ‘tests/test-all.R’ failed.
Last 13 lines of output:
  
  2. Failure: SubjectTag -NA values (@test-OutcomeDatasetFixture.R#58) -----------
  error$message does not match "The column 'SubjectTag' should contain only positive values, but does not.".
  Actual value: "missing value where TRUE/FALSE needed"
  
  
  testthat results ================================================================
  OK: 230 SKIPPED: 0 FAILED: 2
  1. Failure: show AceEstimate shows something (@test-AceEstimationFixture.R#69) 
  2. Failure: SubjectTag -NA values (@test-OutcomeDatasetFixture.R#58) 
  
  Error: testthat unit tests failed
  Execution halted

checking installed package size ... NOTE
  installed size is  6.3Mb
  sub-directories of 1Mb or more:
    data   4.3Mb
    doc    1.0Mb
```

## optmatch (0.9-5)
Maintainer: Mark M. Fredrickson <mark.m.fredrickson@gmail.com>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat-tests.R’ failed.
Last 13 lines of output:
      to be the same as your original data.
  
  Failed -------------------------------------------------------------------------
  1. Failure: Invalid mean.controls input (@test.fullmatch.infeasible.recovery.R#15) 
  error$message does not match "omit.fraction and mean.controls cannot both be specified.".
  Actual value: "omit.fraction and mean.controls cannot both be specified"
  
  
  DONE ===========================================================================
  Error: Test failures
  In addition: Warning message:
  Placing tests in `inst/tests/` is deprecated. Please use `tests/testthat/` instead 
  Execution halted
```

## ParamHelpers (1.7)
Maintainer: Bernd Bischl <bernd_bischl@gmx.net>  
Bug reports: https://github.com/berndbischl/ParamHelpers/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/run-all.R’ failed.
Last 13 lines of output:
  1. Failure: dropParams (@test_dropParams.R#11) 
  2. Failure: filter empty paramset (@test_filterParams.R#5) 
  3. Failure: filter empty paramset (@test_filterParams.R#6) 
  4. Failure: filter empty paramset (@test_filterParams.R#7) 
  5. Failure: filter empty paramset (@test_filterParams.R#8) 
  6. Failure: filter empty paramset (@test_filterParams.R#9) 
  7. Failure: filter empty paramset (@test_filterParams.R#10) 
  8. Failure: filter empty paramset (@test_filterParams.R#11) 
  9. Failure: filter empty paramset (@test_filterParams.R#12) 
  1. ...
  
  Error: testthat unit tests failed
  Execution halted
```

## parsedate (1.1.1)
Maintainer: Gabor Csardi <csardi.gabor@gmail.com>  
Bug reports: https://github.com/gaborcsardi/parsedate/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  1. Error: Filling in is correct (@test-git.r#6) 
  2. Failure: Issue #4 is resolved (@test-git.r#39) 
  3. Failure: Pelago non-matching (@test-iso8601.r#142) 
  4. Failure: Pelago non-matching (@test-iso8601.r#142) 
  5. Failure: Pelago non-matching (@test-iso8601.r#142) 
  6. Failure: Pelago non-matching (@test-iso8601.r#142) 
  7. Failure: Pelago non-matching (@test-iso8601.r#142) 
  8. Failure: Pelago non-matching (@test-iso8601.r#142) 
  9. Failure: Pelago non-matching (@test-iso8601.r#142) 
  1. ...
  
  Error: testthat unit tests failed
  Execution halted
```

## Perc (0.1.1)
Maintainer: Jian Jin <jinjian.pku@gmail.com>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  > library(Perc)
  > 
  > test_check("Perc")
  1. Failure: outputs are of correct format for valueConverter (@test-Converters.R#29) 
  class(vcOutput) produced no output
  
  
  testthat results ================================================================
  OK: 61 SKIPPED: 0 FAILED: 1
  1. Failure: outputs are of correct format for valueConverter (@test-Converters.R#29) 
  
  Error: testthat unit tests failed
  Execution halted
```

## pingr (1.1.0)
Maintainer: "Gabor Csardi" <csardi.gabor@gmail.com>  
Bug reports: https://github.com/gaborcsardi/pingr/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  > if (Sys.getenv("NOT_CRAN") != "") {
  +   test_check("pingr")
  + }
  1. Error: We can ping localhost (@test-tcp.r#13) -------------------------------
  LENGTH or similar applied to closure object
  1: ping_port("127.0.0.1", port = tools:::httpdPort, count = 1) at testthat/test-tcp.r:13
  
  testthat results ================================================================
  OK: 15 SKIPPED: 0 FAILED: 1
  1. Error: We can ping localhost (@test-tcp.r#13) 
  
  Error: testthat unit tests failed
  Execution halted
```

## PKNCA (0.7)
Maintainer: Bill Denney <bill@denney.ws>  
Bug reports: https://github.com/billdenney/pknca/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  
  
  2. Failure: PKNCAresults and summary (@test-data.classes.R#253) ----------------
  myresult <- pk.nca(mydata) showed 0 warnings
  
  
  testthat results ================================================================
  OK: 832 SKIPPED: 0 FAILED: 2
  1. Failure: PKNCAresults and summary (@test-data.classes.R#232) 
  2. Failure: PKNCAresults and summary (@test-data.classes.R#253) 
  
  Error: testthat unit tests failed
  Execution halted
```

## pmc (1.0.1)
Maintainer: Carl Boettiger <cboettig@gmail.com>  
Bug reports: https://github.com/cboettig/pmc/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘ouch’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## poplite (0.99.16)
Maintainer: Daniel Bottomly <bottomly@ohsu.edu>

0 errors | 1 warning  | 3 notes

```
checking running R code from vignettes ... WARNING
Errors in running code in vignettes:
when running code in ‘poplite.Rnw’
  ...
8             8         8    18      0  1.6844357  0.53539884          2     F
9             9         9    20      1  0.9113913 -0.55527835          2     F
10           10        10    12      1  0.2374303  1.77950291          1     M
..          ...       ...   ...    ...        ...         ...        ...   ...

> library(VariantAnnotation)

  When sourcing ‘poplite.R’:
Error: there is no package called ‘VariantAnnotation’
Execution halted


checking package dependencies ... NOTE
Package suggested but not available for checking: ‘VariantAnnotation’

checking R code for possible problems ... NOTE
join,Database : .local: no visible binding for global variable
  ‘new.ancil’

checking re-building of vignette outputs ... NOTE
Error in re-building vignettes:
  ...

    select

The following object is masked from ‘package:stats’:

    filter

... 8 lines ...
Loading required package: DBI
Starting gender
Starting clinical
Starting samples
Starting dna

Error: processing vignette 'poplite.Rnw' failed with diagnostics:
 chunk 15 
Error in library(VariantAnnotation) : 
  there is no package called ‘VariantAnnotation’
Execution halted
```

## prcbench (0.3.2)
Maintainer: Takaya Saito <takaya.saito@outlook.com>  
Bug reports: https://github.com/takayasaito/prcbench/issues

2 errors | 0 warnings | 1 note 

```
checking examples ... ERROR
Running examples in ‘prcbench-Ex.R’ failed
The error most likely occurred in:

> base::assign(".ptime", proc.time(), pos = "CheckExEnv")
> ### Name: autoplot.evalcurve
> ### Title: Plot the result of Precision-Recall curve evaluation
> ### Aliases: autoplot.evalcurve
> 
> ### ** Examples
> 
> library(ggplot2)
> 
> ## Plot evaluation results on test datasets r1, r2, and r3
> testset <- create_testset("curve", c("c1", "c2", "c3"))
> toolset <- create_toolset(set_names = "crv5")
> eres1 <- run_evalcurve(testset, toolset)
Error: PerfMeas needed for this function to work. Please install it.
Execution halted

checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  1. Error: run_benchmark (@test_main_benchmark.R#32) 
  2. Failure: run_benchmark: testset (@test_main_benchmark.R#58) 
  3. Failure: run_benchmark: testset (@test_main_benchmark.R#61) 
  4. Failure: run_benchmark: toolset (@test_main_benchmark.R#84) 
  5. Failure: run_benchmark: toolset (@test_main_benchmark.R#87) 
  6. Error: run_benchmark: times (@test_main_benchmark.R#109) 
  7. Failure: run_benchmark: unit (@test_main_benchmark.R#144) 
  8. Failure: run_benchmark: unit (@test_main_benchmark.R#144) 
  9. Failure: run_benchmark: unit (@test_main_benchmark.R#144) 
  1. ...
  
  Error: testthat unit tests failed
  Execution halted

checking re-building of vignette outputs ... NOTE
Error in re-building vignettes:
  ...
Quitting from lines 119-124 (introduction.Rmd) 
Error: processing vignette 'introduction.Rmd' failed with diagnostics:
PerfMeas needed for this function to work. Please install it.
Execution halted

```

## ProjectTemplate (0.6)
Maintainer: Kirill Mueller <krlmlr+r@mailbox.org>  
Bug reports: https://github.com/johnmyleswhite/ProjectTemplate/issues

1 error  | 0 warnings | 2 notes

```
checking tests ... ERROR
Running the tests in ‘tests/run-all.R’ failed.
Last 13 lines of output:
  
  
  testthat results ================================================================
  OK: 307 SKIPPED: 0 FAILED: 6
  1. Error: All elements have length 1 (@test-load.R#4) 
  2. Failure: Test full project into existing directory (@test-overwrite.R#5) 
  3. Error: Test full project into existing directory (@test-overwrite.R#9) 
  4. Failure: Test minimal project into existing directory with an unrelated entry (@test-overwrite.R#45) 
  5. Error: Test minimal project into existing directory with an unrelated entry (@test-overwrite.R#53) 
  6. Failure: Test failure creating project into existing directory with an unrelated entry if merge.existing is not set (@test-overwrite.R#75) 
  
  Error: testthat unit tests failed
  Execution halted

checking package dependencies ... NOTE
Package suggested but not available for checking: ‘RODBC’

checking DESCRIPTION meta-information ... NOTE
Malformed Title field: should not end in a period.
```

## pvar (2.2)
Maintainer: Vygantas Butkus <Vygantas.Butkus@gmail.com>

1 error  | 0 warnings | 1 note 

```
checking tests ... ERROR
Running the tests in ‘tests/test-all.R’ failed.
Last 13 lines of output:
  Failed -------------------------------------------------------------------------
  1. Error: Basic (@test-pvar.R#14) ----------------------------------------------
  argument "expected" is missing, with no default
  1: expect_that(pvar(rnorm(10), 2), has_names()) at /Users/hadley/Documents/devtools/testthat/revdep/checks/pvar.Rcheck/pvar/tests/test-pvar.R:14
  2: condition(object) at /Users/hadley/Documents/devtools/testthat/R/expect-that.R:22
  3: expect_named(x, expected = expected, ignore.order = ignore.order, ignore.case = ignore.case) at /Users/hadley/Documents/devtools/testthat/R/old-school.R:42
  4: normalise_names(expected, ignore.order, ignore.case) at /Users/hadley/Documents/devtools/testthat/R/expect-named.R:40
  
  DONE ===========================================================================
  Error: Test failures
  In addition: Warning message:
  Placing tests in `inst/tests/` is deprecated. Please use `tests/testthat/` instead 
  Execution halted

checking DESCRIPTION meta-information ... NOTE
Malformed Description field: should contain one or more complete sentences.
```

## pxweb (0.6.0)
Maintainer: Mans Magnusson <mons.magnusson@gmail.com>  
Bug reports: https://github.com/rOpenGov/pxweb/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat_interactive.R’ failed.
Last 13 lines of output:
  
  
  2. Failure: findData.inputBaseCat (@test-interactive_pxweb.R#9) ----------------
  pxweb:::findData.inputBaseCat(c(3, 6), test_codedAlt) produced no output
  
  
  testthat results ================================================================
  OK: 23 SKIPPED: 0 FAILED: 2
  1. Failure: findData.inputBaseCat (@test-interactive_pxweb.R#7) 
  2. Failure: findData.inputBaseCat (@test-interactive_pxweb.R#9) 
  
  Error: testthat unit tests failed
  Execution halted
```

## rAmCharts (2.0.0)
Maintainer: Jeffery Petit <jeffery.petit@datastorm.fr>  
Bug reports: https://github.com/datastorm-open/rAmCharts/issues/

1 error  | 0 warnings | 1 note 

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  error$message does not match "*.toto*.".
  Actual value: "toto must be of class 'numeric' instead of 'logical'"
  
  
  testthat results ================================================================
  OK: 204 SKIPPED: 0 FAILED: 4
  1. Failure: .testNumeric (@test_amTests.R#12) 
  2. Failure: .testLogical (@test_amTests.R#25) 
  3. Failure: .testCharacter (@test_amTests.R#40) 
  4. Failure: .testInterval (@test_amTests.R#54) 
  
  Error: testthat unit tests failed
  Execution halted

checking installed package size ... NOTE
  installed size is  7.1Mb
  sub-directories of 1Mb or more:
    htmlwidgets   5.9Mb
```

## RAppArmor (2.0.1)
Maintainer: Jeroen Ooms <jeroen.ooms@stat.ucla.edu>  
Bug reports: http://github.com/jeroenooms/RAppArmor/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘RAppArmor’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/RAppArmor.Rcheck/00install.out’ for details.
```

## rAvis (0.1.4)
Maintainer: Sara Varela <svarela@paleobiogeography.org>  
Bug reports: https://github.com/ropensci/rAvis/issues

0 errors | 1 warning  | 0 notes

```
checking whether package ‘rAvis’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import ‘maptools::nowrapSpatialLines’ by ‘sp::nowrapSpatialLines’ when loading ‘rAvis’
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/rAvis.Rcheck/00install.out’ for details.
```

## rcrypt (0.1.1)
Maintainer: Brett Klamer <rcrypt@brettklamer.com>

1 error  | 0 warnings | 0 notes

```
checking whether package ‘rcrypt’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/rcrypt.Rcheck/00install.out’ for details.
```

## rDEA (1.2-3)
Maintainer: Jaak Simm <jaak.simm@gmail.com>

1 error  | 0 warnings | 0 notes

```
checking whether package ‘rDEA’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/rDEA.Rcheck/00install.out’ for details.
```

## readGenalex (1.0)
Maintainer: Douglas G. Scofield <douglasgscofield@gmail.com>  
Bug reports: https://github.com/douglasgscofield/readGenalex/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  
  Error: as.genetics(x1) produced no output
  testthat results ================================================================
  OK: 343 SKIPPED: 0 FAILED: 6
  1. Failure: summary.genalex summarises pops etc., genotypes, and extra data (@test_all.R#231) 
  2. Failure: summary.genalex summarises pops etc., genotypes, and extra data (@test_all.R#232) 
  3. Failure: summary.genalex summarises pops etc., genotypes, and extra data (@test_all.R#233) 
  4. Failure: summary.genalex summarises pops etc., genotypes, and extra data (@test_all.R#236) 
  5. Failure: summary.genalex summarises pops etc., genotypes, and extra data (@test_all.R#237) 
  6. Failure: Return is invisible with quiet=FALSE (@test_checkNullAlleles.R#68) 
  
  Error: testthat unit tests failed
  Execution halted
```

## redland (1.0.17-7)
Maintainer: Matthew B. Jones <jones@nceas.ucsb.edu>  
Bug reports: https://github.com/ropensci/redland-bindings/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘redland’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/redland.Rcheck/00install.out’ for details.
```

## Rlibeemd (1.3.7)
Maintainer: Jouni Helske <jouni.helske@jyu.fi>  
Bug reports: https://github.com/helske/Rlibeemd/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘Rlibeemd’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/Rlibeemd.Rcheck/00install.out’ for details.
```

## RLumModel (0.1.0)
Maintainer: Johannes Friedrich <johannes.friedrich@uni-bayreuth.de>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  .set_pars("Pagonis2008") produced no output
  
  
  testthat results ================================================================
  OK: 5 SKIPPED: 0 FAILED: 5
  1. Failure: check inputs set_pars (@test-set_pars.R#4) 
  2. Failure: check inputs set_pars (@test-set_pars.R#5) 
  3. Failure: check inputs set_pars (@test-set_pars.R#6) 
  4. Failure: check inputs set_pars (@test-set_pars.R#7) 
  5. Failure: check inputs set_pars (@test-set_pars.R#8) 
  
  Error: testthat unit tests failed
  Execution halted
```

## rmumps (5.0.1.9-1)
Maintainer: Serguei Sokol <sokol@insa-toulouse.fr>  
Bug reports: https://github.com/sgsokol/rmumps/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘rmumps’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/rmumps.Rcheck/00install.out’ for details.
```

## rnetcarto (0.2.4)
Maintainer: Guilhem Doulcier <guilhem.doulcier@ens.fr>

1 error  | 0 warnings | 0 notes

```
checking whether package ‘rnetcarto’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/rnetcarto.Rcheck/00install.out’ for details.
```

## RNiftyReg (2.2.0)
Maintainer: Jon Clayden <code@clayden.org>  
Bug reports: https://github.com/jonclayden/RNiftyReg/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## RODBCDBI (0.1.1)
Maintainer: Nagi Teramo <teramonagi@gmail.com>

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RODBC’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## rpf (0.51)
Maintainer: Joshua Pritikin <jpritikin@pobox.com>

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## rpivotTable (0.1.5.7)
Maintainer: Enzo Martoglio  <enzo@smartinsightsfromdata.com>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  1. Error: parameters handled correctly (@test_params.R#4) ----------------------
  is.character(object) is not TRUE
  1: expect_match(rpivotTable(data.frame(), rows = c("arow"))$x$params$rows, "arow") at testthat/test_params.R:4
  2: stopifnot(is.character(object)) at /Users/hadley/Documents/devtools/testthat/R/expectations-matches.R:26
  3: stop(sprintf(ngettext(length(r), "%s is not TRUE", "%s are not all TRUE"), ch), call. = FALSE, 
         domain = NA)
  
  testthat results ================================================================
  OK: 11 SKIPPED: 0 FAILED: 1
  1. Error: parameters handled correctly (@test_params.R#4) 
  
  Error: testthat unit tests failed
  Execution halted
```

## rr (1.3)
Maintainer: Graeme Blair <graeme.blair@columbia.edu>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  
  testthat results ================================================================
  OK: 70 SKIPPED: 3 FAILED: 7
  1. Failure: basic code runs when there are covariates sent to the mixed model (@test-bayes-mixed.R#155) 
  2. Failure: standard functions coef, sd.rrreg.bayes, summary work (@test-bayes-mixed.R#219) 
  3. Failure: doing multiple chains works as well as coef, sd.rrreg.bayes, summary work (@test-bayes-mixed.R#339) 
  4. Failure: doing multiple chains works as well as coef, sd.rrreg.bayes, summary work (@test-bayes-mixed.R#343) 
  5. Failure: standard functions coef, sd.rrreg.bayes, summary work (@test-bayes.R#108) 
  6. Failure: doing multiple chains works as well as coef, sd.rrreg.bayes, summary work (@test-bayes.R#164) 
  7. Failure: doing multiple chains works as well as coef, sd.rrreg.bayes, summary work (@test-bayes.R#168) 
  
  Error: testthat unit tests failed
  Execution halted
```

## rsig (1.0)
Maintainer: Sangkyun Lee <sangkyun.lee@tu-dortmund.de>

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘survcomp’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## Rssa (0.13-1)
Maintainer: Anton Korobeynikov <anton@korobeynikov.info>

1 error  | 0 warnings | 0 notes

```
checking whether package ‘Rssa’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/Rssa.Rcheck/00install.out’ for details.
```

## rstanarm (2.9.0-3)
Maintainer: Ben Goodrich <benjamin.goodrich@columbia.edu>  
Bug reports: https://github.com/stan-dev/rstanarm/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Packages required but not available: ‘StanHeaders’ ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## sdcTable (0.20.5)
Maintainer: Bernhard Meindl <bernhard.meindl@statistik.gv.at>  
Bug reports: https://github.com/bernhard-da/sdcTable/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘sdcTable’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/sdcTable.Rcheck/00install.out’ for details.
```

## sdmvspecies (0.3.2)
Maintainer: Xiaoquan Kong <u1mail2me@gmail.com>  
Bug reports: https://github.com/howl-anderson/sdmvspecies/issues

0 errors | 1 warning  | 0 notes

```
checking for executable files ... WARNING
Found the following executable file:
  inst/external/env/bio14.bil
Source packages should not contain undeclared executable files.
See section ‘Package structure’ in the ‘Writing R Extensions’ manual.
```

## sgd (1.1)
Maintainer: Dustin Tran <dustin@cs.columbia.edu>  
Bug reports: https://github.com/airoldilab/sgd/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘sgd’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/sgd.Rcheck/00install.out’ for details.
```

## simr (1.0.1)
Maintainer: Peter Green <greenp@landcareresearch.co.nz>  
Bug reports: https://github.com/pitakakariki/simr/issues

0 errors | 1 warning  | 0 notes

```
checking whether package ‘simr’ can be installed ... WARNING
Found the following significant warnings:
  Warning: package ‘lme4’ was built under R version 3.2.5
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/simr.Rcheck/00install.out’ for details.
```

## SpaDES (1.1.2)
Maintainer: Alex M Chubaty <alexander.chubaty@canada.ca>  
Bug reports: https://github.com/PredictiveEcology/SpaDES/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘secr’

Package suggested but not available for checking: ‘fastshp’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## spaero (0.1.0)
Maintainer: Eamon O'Dea <odea35@gmail.com>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
    expect_equal(hello(), 'Hello World')    
                                        ^~~~
  tests/testthat/test_dir/test-helper.R:7:1: style: Trailing blank lines are superfluous.
  
  ^
  
  
  testthat results ================================================================
  OK: 93 SKIPPED: 0 FAILED: 1
  1. Failure: Package Style (@test-stats.R#4) 
  
  Error: testthat unit tests failed
  Execution halted
```

## spaMM (1.8.0)
Maintainer: François Rousset <francois.rousset@umontpellier.fr>

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## sparseHessianFD (0.3.0)
Maintainer: Michael Braun <braunm@smu.edu>

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## spduration (0.15.0)
Maintainer: Andreas Beger <adbeger@gmail.com>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  plot_hazard(model.coups, zvals = c(1, -5), ci = FALSE, col = "blue") produced no output
  
  
  testthat results ================================================================
  OK: 17 SKIPPED: 0 FAILED: 5
  1. Failure: plot_hazard accepts all input options (@test_plotting.R#8) 
  2. Failure: plot_hazard accepts all input options (@test_plotting.R#10) 
  3. Failure: plot_hazard accepts all input options (@test_plotting.R#13) 
  4. Failure: plot_hazard accepts all input options (@test_plotting.R#17) 
  5. Failure: plot_hazard accepts all input options (@test_plotting.R#22) 
  
  Error: testthat unit tests failed
  Execution halted
```

## StableEstim (2.0)
Maintainer: Tarak Kharrat <tarak.kharrat@manchester.ac.uk>

1 error  | 0 warnings | 0 notes

```
checking examples ... ERROR
Running examples in ‘StableEstim-Ex.R’ failed
The error most likely occurred in:

> base::assign(".ptime", proc.time(), pos = "CheckExEnv")
> ### Name: expect_almost_equal
> ### Title: test approximate equality
> ### Aliases: expect_almost_equal
> ### Keywords: general-functions
> 
> ### ** Examples
> 
> x=1.1 ; y=1.5
> expect_almost_equal(x,y,1) ## pass
Error in match.arg(type, c("success", "failure", "error", "skip", "warning")) : 
  'arg' must be NULL or a character vector
Calls: expect_almost_equal ... expect_that -> condition -> expectation -> match.arg
Execution halted
```

## stablespec (0.1.3)
Maintainer: Ridho Rahmadi <r.rahmadi@cs.ru.nl>

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Packages required but not available: ‘graph’ ‘Rgraphviz’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## statar (0.6.0)
Maintainer: Matthieu Gomez <mattg@princeton.edu>  
Bug reports: https://github.com/matthieugomez/statar/issues

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  
  The following objects are masked from 'package:lubridate':
  
      hour, mday, month, quarter, wday, week, yday, year
  
  testthat results ================================================================
  OK: 35 SKIPPED: 0 FAILED: 3
  1. Failure: conversion works (@test_elapsed.R#14) 
  2. Failure: rounding (@test_elapsed.R#20) 
  3. Failure: rounding (@test_elapsed.R#21) 
  
  Error: testthat unit tests failed
  Execution halted
```

## storr (1.0.0)
Maintainer: Rich FitzJohn <rich.fitzjohn@gmail.com>

1 error  | 0 warnings | 1 note 

```
checking examples ... ERROR
Running examples in ‘storr-Ex.R’ failed
The error most likely occurred in:

> base::assign(".ptime", proc.time(), pos = "CheckExEnv")
> ### Name: test_driver
> ### Title: Test a storr driver
> ### Aliases: test_driver
> 
> ### ** Examples
> 
> ## Testing the environment driver is nice and fast:
> if (requireNamespace("testthat")) {
+   test_driver(function() driver_environment())
+ }
Loading required namespace: testthat
Error in test_driver(function() driver_environment()) : 
  attempt to apply non-function
Execution halted

checking re-building of vignette outputs ... NOTE
Error in re-building vignettes:
  ...
Quitting from lines 419-420 (drivers.Rmd) 
Error: processing vignette 'drivers.Rmd' failed with diagnostics:
attempt to apply non-function
Execution halted

```

## strvalidator (1.6.0)
Maintainer: Oskar Hansson <oskar.hansson@fhi.no>  
Bug reports: https://github.com/OskarHansson/strvalidator/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘strvalidator’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/strvalidator.Rcheck/00install.out’ for details.
```

## swirlify (0.4.1)
Maintainer: Sean Kross <sean@seankross.com>

0 errors | 1 warning  | 0 notes

```
checking whether package ‘swirlify’ can be installed ... WARNING
Found the following significant warnings:
  Warning: package ‘swirl’ was built under R version 3.2.5
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/swirlify.Rcheck/00install.out’ for details.
```

## testthatsomemore (0.1)
Maintainer: Robert Krzyzanowski <technoguyrob@gmail.com>

1 error  | 0 warnings | 0 notes

```
checking examples ... ERROR
Running examples in ‘testthatsomemore-Ex.R’ failed
The error most likely occurred in:

> base::assign(".ptime", proc.time(), pos = "CheckExEnv")
> ### Name: assert
> ### Title: Explicitly state that we expect no errors to occur.
> ### Aliases: assert
> 
> ### ** Examples
> 
> assert(1 + 1) # This will throw no error.
> stopifnot(is(tryCatch(error = identity, assert(not_existent)), 'error'))
Error: is(result, "error") isn't false.
Execution halted
```

## tigris (0.2.2)
Maintainer: Kyle Walker <kyle.walker@tcu.edu>

0 errors | 1 warning  | 0 notes

```
checking whether package ‘tigris’ can be installed ... WARNING
Found the following significant warnings:
  Warning: replacing previous import ‘maptools::nowrapSpatialLines’ by ‘sp::nowrapSpatialLines’ when loading ‘tigris’
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/tigris.Rcheck/00install.out’ for details.
```

## tmod (0.24)
Maintainer: January Weiner <january.weiner@gmail.com>

2 errors | 0 warnings | 2 notes

```
checking examples ... ERROR
Running examples in ‘tmod-Ex.R’ failed
The error most likely occurred in:

> base::assign(".ptime", proc.time(), pos = "CheckExEnv")
> ### Name: tmodLimmaTest
> ### Title: Run tmod enrichment tests directly on a limma object
> ### Aliases: tmodLimmaTest
> 
> ### ** Examples
> 
> library(limma)
Error in library(limma) : there is no package called ‘limma’
Execution halted

checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  
  
  2. Failure: tmod is sane (@test_data.R#8) --------------------------------------
  `tmod` produced no output
  
  
  testthat results ================================================================
  OK: 15 SKIPPED: 0 FAILED: 2
  1. Failure: tmod is sane (@test_data.R#7) 
  2. Failure: tmod is sane (@test_data.R#8) 
  
  Error: testthat unit tests failed
  Execution halted

checking package dependencies ... NOTE
Packages suggested but not available for checking: ‘limma’ ‘org.Hs.eg.db’

checking re-building of vignette outputs ... NOTE
Error in re-building vignettes:
  ...
Quitting from lines 46-56 (tmod.rmd) 
Error: processing vignette 'tmod.rmd' failed with diagnostics:
there is no package called 'limma'
Execution halted

```

## toaster (0.5.1)
Maintainer: Gregory Kanevsky <gregory.kanevsky@teradata.com>  
Bug reports: https://github.com/teradata-aster-field/toaster/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RODBC’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## trustOptim (0.8.5)
Maintainer: Michael Braun <braunm@smu.edu>

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## tsPI (1.0.1)
Maintainer: Jouni Helske <jouni.helske@jyu.fi>  
Bug reports: https://github.com/helske/tsPI/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘tsPI’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/tsPI.Rcheck/00install.out’ for details.
```

## useful (1.2.0)
Maintainer: Jared P. Lander <packages@jaredlander.com>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
  4. Failure: simple.impute.default properly imputes the mean (@test-simple-impute.r#41) 
  all.equal(...) produced no output
  
  
  testthat results ================================================================
  OK: 324 SKIPPED: 0 FAILED: 4
  1. Failure: simple.impute.default properly imputes the mean (@test-simple-impute.r#32) 
  2. Failure: simple.impute.default properly imputes the mean (@test-simple-impute.r#35) 
  3. Failure: simple.impute.default properly imputes the mean (@test-simple-impute.r#38) 
  4. Failure: simple.impute.default properly imputes the mean (@test-simple-impute.r#41) 
  
  Error: testthat unit tests failed
  Execution halted
```

## V8 (1.0.1)
Maintainer: Jeroen Ooms <jeroen.ooms@stat.ucla.edu>  
Bug reports: https://github.com/jeroenooms/v8/issues

1 error  | 0 warnings | 0 notes

```
checking whether package ‘V8’ can be installed ... ERROR
Installation failed.
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/V8.Rcheck/00install.out’ for details.
```

## vartors (0.2.6)
Maintainer: Joris Muller <joris.muller@etu.unistra.fr>  
Bug reports: https://github.com/jomuller/vartors/issues/new

1 error  | 0 warnings | 1 note 

```
checking tests ... ERROR
Running the tests in ‘tests/test-all.R’ failed.
Last 13 lines of output:
  OK: 102 SKIPPED: 0 FAILED: 8
  1. Failure: rep_columns_names should be placed properly (@test-DatabaseDef.R#35) 
  2. Failure: numeric var for Rmd_fr template (@test-Rmd_fr_template.R#21) 
  3. Failure: add default values (@test-VariableDef.R#83) 
  4. Failure: add default values (@test-VariableDef.R#84) 
  5. Failure: DatabaseDef create_script methods (@test-create_script.R#49) 
  6. Failure: header and footer could be turn off (@test-create_script.R#71) 
  7. Failure: header and footer could be turn off (@test-create_script.R#74) 
  8. Failure: fix7 : when no label given with level, names=levels (@test-create_script.R#79) 
  
  Error: testthat unit tests failed
  In addition: There were 31 warnings (use warnings() to see them)
  Execution halted

checking R code for possible problems ... NOTE
descvars_skeleton: no visible binding for global variable ‘example_df’
```

## walkr (0.3.3)
Maintainer: Andy Yao <andy.yao17@gmail.com>  
Bug reports: https://github.com/andyyao95/walkr/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RcppEigen’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## wgsea (1.8)
Maintainer: Chris Wallace <chris.wallace@cimr.cam.ac.uk>

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘snpStats’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## yCrypticRNAs (0.99.2)
Maintainer: Nicole Uwimana <nicole.uwimana@gmail.com>  
Bug reports: https://bitbucket.org/nuwimana/ycrypticrnas/issues

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Packages required but not available: ‘biomaRt’ ‘IRanges’ ‘Rsamtools’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## ZeligChoice (0.9-0)
Maintainer: James Honaker <zelig-zee@iq.harvard.edu>

0 errors | 1 warning  | 0 notes

```
checking whether package ‘ZeligChoice’ can be installed ... WARNING
Found the following significant warnings:
  Warning: namespace ‘Rgraphviz’ is not available and has been replaced
See ‘/Users/hadley/Documents/devtools/testthat/revdep/checks/ZeligChoice.Rcheck/00install.out’ for details.
```

## zoon (0.4.23)
Maintainer: Tom August <tomaug@ceh.ac.uk>

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required and available but unsuitable version: ‘raster’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

