<!--- DO NOT EDIT - Generated by ToolsLister at 2019-07-04T06:20:34.698-->
# Supported Report Formats

Jenkins' Warnings Next Generation Plugin supports the following report formats. 
If your tool is supported, but has no custom icon yet, please file a pull request for the
[Warnings Next Generation Plugin](https://github.com/jenkinsci/warnings-ng-plugin/pulls).

If your tool is not yet supported you can
1. define a new Groovy based parser in the user interface
2. export the issues of your tool to the native XML format (or any other format)
3. provide a parser within a new small plugin. 

If the parser is useful for 
other teams as well please share it and provide pull requests for the 
[Warnings Next Generation Plug-in](https://github.com/jenkinsci/warnings-ng-plugin/pulls) and 
the [Analysis Parsers Library](https://github.com/jenkinsci/analysis-model/). 

| Number | ID | Symbol | Icons | Name | Default Pattern |
| --- | --- | --- | --- | --- | --- |
| 0 | acu-cobol | acuCobol() | - - | AcuCobol Compiler |  |
| 1 | gnat | gnat() | - - | Ada Compiler (gnat) |  |
| 2 | android-lint | androidLintParser() | ![Android Lint](src/main/webapp/icons/android-lint-24x24.png) ![Android Lint](src/main/webapp/icons/android-lint-48x48.png) | Android Lint |  |
| 3 | ansiblelint | ansibleLint() | - - | Ansible Lint |  |
| 4 | armcc | armCc() | - - | Armcc Compiler |  |
| 5 | aspectj | ajc() | - - | AspectJ Compiler |  |
| 6 | axivion-suite | axivionSuite() | - - | Axivion Suite | - |
| 7 | buckminster | buckminster() | - - | Buckminster |  |
| 8 | cadence | cadence() | - - | Cadence Incisive |  |
| 9 | cargo | cargo() | - - | Cargo |  |
| 10 | ccm | ccm() | - - | CCM |  |
| 11 | checkstyle | checkStyle() | ![CheckStyle](src/main/webapp/icons/checkstyle-24x24.png) ![CheckStyle](src/main/webapp/icons/checkstyle-48x48.png) | [CheckStyle](https://checkstyle.org) | **/checkstyle-result.xml |
| 12 | clang | clang() | - - | Clang (LLVM based) |  |
| 13 | clang-tidy | clangTidy() | - - | Clang-Tidy |  |
| 14 | cmake | cmake() | - - | CMake |  |
| 15 | code-analysis | codeAnalysis() | - - | CodeAnalysis |  |
| 16 | codenarc | codeNarc() | - - | CodeNarc |  |
| 17 | coolflux | coolflux() | - - | Coolflux DSP Compiler |  |
| 18 | cpd | cpd() | ![CPD](src/main/webapp/icons/dry-24x24.png) ![CPD](src/main/webapp/icons/dry-48x48.png) | [CPD](https://pmd.github.io/latest/pmd_userdocs_cpd.html) | **/cpd.xml |
| 19 | cppcheck | cppCheck() | - - | CPPCheck |  |
| 20 | cpplint | cppLint() | - - | CppLint |  |
| 21 | csslint | cssLint() | - - | CssLint |  |
| 22 | detekt | detekt() | - - | [Detekt](https://arturbosch.github.io/detekt/) |  |
| 23 | docfx | docFx() | - - | DocFX |  |
| 24 | doxygen | doxygen() | - - | Doxygen |  |
| 25 | dr-memory | drMemory() | - - | Dr. Memory |  |
| 26 | dscanner | dscanner() | - - | [DScanner](https://github.com/dlang-community/D-Scanner) | **/dscanner-report.json |
| 27 | eclipse | eclipse() | - - | Eclipse ECJ |  |
| 28 | erlc | erlc() | - - | Erlang Compiler (erlc) |  |
| 29 | error-prone | errorProne() | ![Error Prone](src/main/webapp/icons/bug-24x24.png) ![Error Prone](src/main/webapp/icons/bug-48x48.png) | [Error Prone](https://errorprone.info) |  |
| 30 | eslint | esLint() | ![ESlint](src/main/webapp/icons/eslint-24x24.png) ![ESlint](src/main/webapp/icons/eslint-48x48.png) | [ESlint](https://eslint.org) |  |
| 31 | findbugs | findBugs() | ![FindBugs](src/main/webapp/icons/findbugs-24x24.png) ![FindBugs](src/main/webapp/icons/findbugs-48x48.png) | FindBugs | **/findbugsXml.xml |
| 32 | flake8 | flake8() | - - | Flake8 |  |
| 33 | flex | flexSdk() | - - | Flex SDK Compiler |  |
| 34 | fxcop | fxcop() | - - | FxCop |  |
| 35 | gendarme | gendarme() | - - | Gendarme |  |
| 36 | ghs-multi | ghsMulti() | - - | GHS Multi Compiler |  |
| 37 | gcc3 | gcc3() | - - | GNU C Compiler (gcc 3 and older) |  |
| 38 | gcc | gcc() | - - | GNU C Compiler (gcc) |  |
| 39 | fortran | gnuFortran() | - - | GNU Fortran Compiler |  |
| 40 | golint | goLint() | ![Go Lint](src/main/webapp/icons/golint-24x24.png) ![Go Lint](src/main/webapp/icons/golint-48x48.png) | Go Lint |  |
| 41 | go-vet | goVet() | - - | Go Vet |  |
| 42 | groovy | groovyScript() | - - | Groovy Parser |  |
| 43 | iar-cstat | iarCstat() | - - | IAR C-STAT |  |
| 44 | iar | iar() | - - | IAR Compiler (C/C&#43;&#43;) |  |
| 45 | iblinter | ibLinter() | - - | [IBLinter](https://github.com/IBDecodable/IBLinter) |  |
| 46 | xlc | xlc() | - - | IBM XLC Compiler |  |
| 47 | infer | infer() | - - | [Infer](http://fbinfer.com) |  |
| 48 | intel | intel() | - - | Intel Compiler (C, Fortran) |  |
| 49 | idea | ideaInspection() | ![IntelliJ IDEA Inspections](src/main/webapp/icons/idea-24x24.png) ![IntelliJ IDEA Inspections](src/main/webapp/icons/idea-48x48.png) | [IntelliJ IDEA Inspections](https://www.jetbrains.com/help/idea/code-inspection.html) |  |
| 50 | java | java() | ![Java](src/main/webapp/icons/java-24x24.png) ![Java](src/main/webapp/icons/java-48x48.png) | Java |  |
| 51 | javadoc-warnings | javaDoc() | ![JavaDoc](src/main/webapp/icons/java-24x24.png) ![JavaDoc](src/main/webapp/icons/java-48x48.png) | JavaDoc |  |
| 52 | jc-report | jcReport() | - - | JCReport |  |
| 53 | js-hint | jsHint() | - - | JSHint |  |
| 54 | jslint | jsLint() | - - | [JSLint](https://www.jslint.com) |  |
| 55 | klocwork | klocWork() | - - | Klocwork |  |
| 56 | kotlin | kotlin() | ![Kotlin](src/main/webapp/icons/kotlin-24x24.png) ![Kotlin](src/main/webapp/icons/kotlin-48x48.png) | Kotlin |  |
| 57 | ktlint | ktLint() | ![Ktlint](src/main/webapp/icons/ktlint-24x24.png) ![Ktlint](src/main/webapp/icons/ktlint-48x48.png) | [Ktlint](https://ktlint.github.io) |  |
| 58 | maven-warnings | mavenConsole() | - - | Maven |  |
| 59 | taglist | tagList() | - - | [Maven Taglist Plugin](https://www.mojohaus.org/taglist-maven-plugin) | **/taglist.xml |
| 60 | modelsim | modelsim() | - - | MentorGraphics Modelsim/Questa |  |
| 61 | metrowerks | metrowerksCodeWarrior() | - - | Metrowerks CodeWarrior |  |
| 62 | msbuild | msBuild() | - - | MSBuild |  |
| 63 | mypy | myPy() | - - | MyPy |  |
| 64 | nag-fortran | nagFortran() | - - | NAG Fortran Compiler |  |
| 65 | open-tasks | taskScanner() | ![Open Tasks Scanner](src/main/webapp/icons/open-tasks-24x24.png) ![Open Tasks Scanner](src/main/webapp/icons/open-tasks-48x48.png) | Open Tasks Scanner | - |
| 66 | invalids | invalids() | - - | Oracle Invalids |  |
| 67 | pclint | pcLint() | - - | PC-Lint |  |
| 68 | pep8 | pep8() | - - | Pep8 |  |
| 69 | perforce | perforce() | - - | Perforce Compiler |  |
| 70 | perl-critic | perlCritic() | - - | Perl::Critic |  |
| 71 | php | php() | - - | PHP Runtime |  |
| 72 | php-code-sniffer | phpCodeSniffer() | - - | [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) |  |
| 73 | phpstan | phpStan() | ![PHPStan](src/main/webapp/icons/phpstan-24x24.png) ![PHPStan](src/main/webapp/icons/phpstan-48x48.png) | [PHPStan](https://github.com/phpstan/phpstan) |  |
| 74 | pit | pit() | ![Pit Test Coverage](src/main/webapp/icons/pit-24x24.png) ![Pit Test Coverage](src/main/webapp/icons/pit-48x48.png) | [Pit Test Coverage](http://pitest.org) |  |
| 75 | pmd | pmdParser() | ![PMD](src/main/webapp/icons/pmd-24x24.png) ![PMD](src/main/webapp/icons/pmd-48x48.png) | [PMD](https://pmd.github.io) | **/pmd.xml |
| 76 | prefast | prefast() | - - | PREfast |  |
| 77 | puppetlint | puppetLint() | - - | Puppet-Lint |  |
| 78 | pydocstyle | pyDocStyle() | - - | Pydocstyle |  |
| 79 | pylint | pyLint() | ![Pylint](src/main/webapp/icons/pylint-24x24.png) ![Pylint](src/main/webapp/icons/pylint-48x48.png) | Pylint |  |
| 80 | qac | qacSourceCodeAnalyser() | - - | QA-C Sourcecode Analyser |  |
| 81 | dupfinder | dupFinder() | ![Resharper dupFinder](src/main/webapp/icons/dry-24x24.png) ![Resharper dupFinder](src/main/webapp/icons/dry-48x48.png) | Resharper dupFinder |  |
| 82 | resharper | resharperInspectCode() | ![Resharper InspectCode](src/main/webapp/icons/resharper-24x24.png) ![Resharper InspectCode](src/main/webapp/icons/resharper-48x48.png) | Resharper InspectCode |  |
| 83 | robocopy | robocopy() | - - | Robocopy |  |
| 84 | rflint | rfLint() | ![Robot Framework Lint](src/main/webapp/icons/robot-framework-24x24.png) ![Robot Framework Lint](src/main/webapp/icons/robot-framework-48x48.png) | Robot Framework Lint |  |
| 85 | rubocop | ruboCop() | ![RuboCop](src/main/webapp/icons/rubocop-24x24.png) ![RuboCop](src/main/webapp/icons/rubocop-48x48.png) | RuboCop |  |
| 86 | scala | scala() | ![Scala Compiler](src/main/webapp/icons/scala-24x24.png) ![Scala Compiler](src/main/webapp/icons/scala-48x48.png) | Scala Compiler |  |
| 87 | simian | simian() | ![Simian](src/main/webapp/icons/dry-24x24.png) ![Simian](src/main/webapp/icons/dry-48x48.png) | Simian |  |
| 88 | sonar | sonarQube() | ![SonarQube](src/main/webapp/icons/sonar-24x24.png) ![SonarQube](src/main/webapp/icons/sonar-48x48.png) | SonarQube | **/sonar-report.json |
| 89 | sphinx | sphinxBuild() | - - | Sphinx-build |  |
| 90 | spotbugs | spotBugs() | ![SpotBugs](src/main/webapp/icons/spotbugs-24x24.png) ![SpotBugs](src/main/webapp/icons/spotbugs-48x48.png) | [SpotBugs](https://spotbugs.github.io) | **/spotbugsXml.xml |
| 91 | stylecop | styleCop() | - - | StyleCop |  |
| 92 | sunc | sunC() | - - | SUN C&#43;&#43; Compiler |  |
| 93 | swiftlint | swiftLint() | - - | [SwiftLint](https://github.com/realm/SwiftLint) |  |
| 94 | tasking-vx | taskingVx() | - - | TASKING VX Compiler |  |
| 95 | code-composer | tiCss() | - - | Texas Instruments Code Composer Studio |  |
| 96 | tnsdl | tnsdl() | - - | TNSDL Translator |  |
| 97 | tslint | tsLint() | - - | [TSLint](https://palantir.github.io/tslint/) |  |
| 98 | issues | issues() | - - | [Warnings Plugin Native Format](https://github.com/jenkinsci/warnings-ng-plugin/blob/master/doc/Documentation.md#export-your-issues-into-a-supported-format) |  |
| 99 | diabc | diabC() | - - | Wind River Diab Compiler (C/C&#43;&#43;) |  |
| 100 | xmllint | xmlLint() | - - | XML Lint |  |
| 101 | yamllint | yamlLint() | - - | [YamlLint](https://yamllint.readthedocs.io/) |  |
| 102 | yui | yuiCompressor() | - - | YUI Compressor |  |
| 103 | zptlint | zptLint() | - - | ZPT Lint |  |
