---
id: 12971
title: setuptools
date: 2020-02-14
author: auto-mik
layout: post
permalink: /python/setuptools/
image:
category:
   - python
tags:  
   - setuptools
---
Easily download, build, install, upgrade, and uninstall Python packages

Number of Python files 145.

---
file name: folder/setuptools-45.2.0/conftest.py 
(537 characters, 38 words)
import modules: [sys] 
classes: 
functions: [pytest_addoption] 

---
file name: folder/setuptools-45.2.0/setup.py 
(5990 characters, 384 words)
import modules: [os] [sys] [setuptools] 
classes: 
functions: [require_metadata] [read_commands] [_gen_console_scripts] [pypi_link] 

---
file name: folder/setuptools-45.2.0/pavement.py 
(1514 characters, 134 words)
import modules: [re] [sys] [subprocess] [paver.easy] 
classes: 
functions: [remove_all] [update_vendored] [rewrite_packaging] [clean] [install] [update_pkg_resources] [update_setuptools] 

---
file name: folder/setuptools-45.2.0/easy_install.py 
(126 characters, 13 words)
import modules: 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/bootstrap.py 
(1648 characters, 136 words)
import modules: [__future__] [os] [sys] [textwrap] [subprocess] [io] 
classes: 
functions: [ensure_egg_info] [add_minimal_info] [run_egg_info] 

---
file name: folder/setuptools-45.2.0/pkg_resources/__init__.py 
(108396 characters, 10413 words)
import modules: [__future__] [sys] [os] [io] [time] [re] [types] [zipfile] [zipimport] [warnings] [stat] [functools] [pkgutil] [operator] [platform] [collections] [plistlib] [email.parser] [errno] [tempfile] [textwrap] [itertools] [inspect] [ntpath] [posixpath] [pkgutil] [pkg_resources.extern] [pkg_resources.extern.six.moves] [os] [os.path] [None] [pkg_resources.extern] [pkg_resources.extern] 
classes: [PEP440Warning] [ResolutionError] [VersionConflict] [ContextualVersionConflict] [DistributionNotFound] [UnknownExtra] [IMetadataProvider] [IResourceProvider] [WorkingSet] [_ReqExtras] [Environment] [ExtractionError] [ResourceManager] [NullProvider] [EggProvider] [DefaultProvider] [EmptyProvider] [ZipManifests] [MemoizedZipManifests] [ZipProvider] [FileMetadata] [PathMetadata] [EggMetadata] [NoDists] [EntryPoint] [Distribution] [EggInfoDistribution] [DistInfoDistribution] [RequirementParseError] [Requirement] [PkgResourcesDeprecationWarning] 
functions: [parse_version] [_declare_state] [__getstate__] [__setstate__] [_sget_dict] [_sset_dict] [_sget_object] [_sset_object] [get_supported_platform] [register_loader_type] [get_provider] [_macosx_vers] [_macosx_arch] [get_build_platform] [compatible_platforms] [run_script] [get_distribution] [load_entry_point] [get_entry_map] [get_entry_info] [get_default_cache] [safe_name] [safe_version] [safe_extra] [to_filename] [invalid_marker] [evaluate_marker] [register_finder] [find_distributions] [find_eggs_in_zip] [find_nothing] [_by_version_descending] [find_on_path] [dist_factory] [safe_listdir] [distributions_from_metadata] [non_empty_lines] [resolve_egg_link] [register_namespace_handler] [_handle_ns] [_rebuild_mod_path] [declare_namespace] [fixup_namespace_packages] [file_ns_handler] [null_ns_handler] [normalize_path] [_cygwin_patch] [_normalize_cached] [_is_egg_path] [_is_unpacked_egg] [_set_parent_ns] [yield_lines] [_remove_md5_fragment] [_version_from_file] [issue_warning] [parse_requirements] [_always_object] [_find_adapter] [ensure_directory] [_bypass_ensure_directory] [split_sections] [_mkstemp] [_call_aside] [_initialize] [_initialize_master_working_set] 

---
file name: folder/setuptools-45.2.0/pkg_resources/py2_warn.py 
(723 characters, 104 words)
import modules: [sys] [warnings] [textwrap] 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/pkg_resources/py31compat.py 
(558 characters, 65 words)
import modules: [os] [errno] [sys] [extern] 
classes: 
functions: [_makedirs_31] 

---
file name: folder/setuptools-45.2.0/pkg_resources/_vendor/pyparsing.py 
(226313 characters, 22793 words)
import modules: [string] [copy] [sys] [warnings] [re] [sre_constants] [collections] [pprint] [traceback] [types] [datetime] 
classes: [_Constants] [ParseBaseException] [ParseException] [ParseFatalException] [ParseSyntaxException] [RecursiveGrammarException] [_ParseResultsWithOffset] [ParseResults] [ParserElement] [Token] [Empty] [NoMatch] [Literal] [Keyword] [CaselessLiteral] [CaselessKeyword] [CloseMatch] [Word] [Regex] [QuotedString] [CharsNotIn] [White] [_PositionToken] [GoToColumn] [LineStart] [LineEnd] [StringStart] [StringEnd] [WordStart] [WordEnd] [ParseExpression] [And] [Or] [MatchFirst] [Each] [ParseElementEnhance] [FollowedBy] [NotAny] [_MultipleMatch] [OneOrMore] [ZeroOrMore] [_NullToken] [Optional] [SkipTo] [Forward] [_ForwardNoRecurse] [TokenConverter] [Combine] [Group] [Dict] [Suppress] [OnlyOnce] [pyparsing_common] 
functions: [_xml_escape] [col] [lineno] [line] [_defaultStartDebugAction] [_defaultSuccessDebugAction] [_defaultExceptionDebugAction] [nullDebugAction] [_trim_arity] [traceParseAction] [delimitedList] [countedArray] [_flatten] [matchPreviousLiteral] [matchPreviousExpr] [_escapeRegexRangeChars] [oneOf] [dictOf] [originalTextFor] [ungroup] [locatedExpr] [srange] [matchOnlyAtCol] [replaceWith] [removeQuotes] [tokenMap] [_makeTags] [makeHTMLTags] [makeXMLTags] [withAttribute] [withClass] [infixNotation] [nestedExpr] [indentedBlock] [replaceHTMLEntity] 

---
file name: folder/setuptools-45.2.0/pkg_resources/_vendor/__init__.py 
(0 characters, 0 words)
import modules: 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/pkg_resources/_vendor/six.py 
(30098 characters, 2532 words)
import modules: [__future__] [functools] [itertools] [operator] [sys] [types] 
classes: [_LazyDescr] [MovedModule] [_LazyModule] [MovedAttribute] [_SixMetaPathImporter] [_MovedItems] [Module_six_moves_urllib_parse] [Module_six_moves_urllib_error] [Module_six_moves_urllib_request] [Module_six_moves_urllib_response] [Module_six_moves_urllib_robotparser] [Module_six_moves_urllib] 
functions: [_add_doc] [_import_module] [add_move] [remove_move] [assertCountEqual] [assertRaisesRegex] [assertRegex] [with_metaclass] [add_metaclass] [python_2_unicode_compatible] 

---
file name: folder/setuptools-45.2.0/pkg_resources/_vendor/appdirs.py 
(24701 characters, 2590 words)
import modules: [sys] [os] 
classes: [AppDirs] 
functions: [user_data_dir] [site_data_dir] [user_config_dir] [site_config_dir] [user_cache_dir] [user_state_dir] [user_log_dir] [_get_win_folder_from_registry] [_get_win_folder_with_pywin32] [_get_win_folder_with_ctypes] [_get_win_folder_with_jna] 

---
file name: folder/setuptools-45.2.0/pkg_resources/_vendor/packaging/requirements.py 
(4355 characters, 438 words)
import modules: [__future__] [string] [re] [pkg_resources.extern.pyparsing] [pkg_resources.extern.pyparsing] [markers] [specifiers] 
classes: [InvalidRequirement] [Requirement] 
functions: 

---
file name: folder/setuptools-45.2.0/pkg_resources/_vendor/packaging/version.py 
(11556 characters, 1237 words)
import modules: [__future__] [collections] [itertools] [re] [_structures] 
classes: [InvalidVersion] [_BaseVersion] [LegacyVersion] [Version] 
functions: [parse] [_parse_version_parts] [_legacy_cmpkey] [_parse_letter_version] [_parse_local_version] [_cmpkey] 

---
file name: folder/setuptools-45.2.0/pkg_resources/_vendor/packaging/__about__.py 
(720 characters, 93 words)
import modules: [__future__] 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/pkg_resources/_vendor/packaging/_compat.py 
(860 characters, 123 words)
import modules: [__future__] [sys] 
classes: 
functions: [with_metaclass] 

---
file name: folder/setuptools-45.2.0/pkg_resources/_vendor/packaging/markers.py 
(8248 characters, 778 words)
import modules: [__future__] [operator] [os] [platform] [sys] [pkg_resources.extern.pyparsing] [pkg_resources.extern.pyparsing] [_compat] [specifiers] 
classes: [InvalidMarker] [UndefinedComparison] [UndefinedEnvironmentName] [Node] [Variable] [Value] [Op] [Marker] 
functions: [_coerce_parse_result] [_format_marker] [_eval_op] [_get_env] [_evaluate_markers] [format_full_version] [default_environment] 

---
file name: folder/setuptools-45.2.0/pkg_resources/_vendor/packaging/utils.py 
(421 characters, 57 words)
import modules: [__future__] [re] 
classes: 
functions: [canonicalize_name] 

---
file name: folder/setuptools-45.2.0/pkg_resources/_vendor/packaging/__init__.py 
(513 characters, 65 words)
import modules: [__future__] [__about__] 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/pkg_resources/_vendor/packaging/specifiers.py 
(28025 characters, 2944 words)
import modules: [__future__] [abc] [functools] [itertools] [re] [_compat] [version] 
classes: [InvalidSpecifier] [BaseSpecifier] [_IndividualSpecifier] [LegacySpecifier] [Specifier] [SpecifierSet] 
functions: [_require_version_compare] [_version_split] [_pad_version] 

---
file name: folder/setuptools-45.2.0/pkg_resources/_vendor/packaging/_structures.py 
(1416 characters, 140 words)
import modules: [__future__] 
classes: [Infinity] [NegativeInfinity] 
functions: 

---
file name: folder/setuptools-45.2.0/pkg_resources/extern/__init__.py 
(2498 characters, 247 words)
import modules: [sys] 
classes: [VendorImporter] 
functions: 

---
file name: folder/setuptools-45.2.0/pkg_resources/tests/test_find_distributions.py 
(1274 characters, 92 words)
import modules: [py] [pytest] [pkg_resources] 
classes: [TestFindDistributions] 
functions: 

---
file name: folder/setuptools-45.2.0/pkg_resources/tests/test_resources.py 
(31077 characters, 2310 words)
import modules: [__future__] [os] [sys] [string] [platform] [itertools] [pkg_resources.extern.six.moves] [pytest] [pkg_resources.extern] [pkg_resources] [pkg_resources] 
classes: [Metadata] [TestDistro] [TestWorkingSet] [TestEntryPoints] [TestRequirements] [TestParsing] [TestNamespaces] 
functions: [pairwise] 

---
file name: folder/setuptools-45.2.0/pkg_resources/tests/test_markers.py 
(227 characters, 16 words)
import modules: [mock] [pkg_resources] 
classes: 
functions: [test_ordering] 

---
file name: folder/setuptools-45.2.0/pkg_resources/tests/test_pkg_resources.py 
(14423 characters, 1296 words)
import modules: [__future__] [sys] [tempfile] [os] [zipfile] [datetime] [time] [subprocess] [stat] [distutils.dist] [distutils.command.install_egg_info] [pkg_resources] [setuptools.extern] [pkg_resources.extern.six.moves] [pkg_resources.extern.six] [pytest] [pkg_resources] 
classes: [EggRemover] [TestZipProvider] [TestResourceManager] [TestDeepVersionLookupDistutils] 
functions: [timestamp] [make_test_distribution] [test_get_metadata__bad_utf8] [touch_file] [make_distribution_no_version] [test_distribution_version_missing] [test_distribution_version_missing_undetected_path] 

---
file name: folder/setuptools-45.2.0/pkg_resources/tests/__init__.py 
(0 characters, 0 words)
import modules: 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/pkg_resources/tests/test_working_set.py 
(8354 characters, 646 words)
import modules: [inspect] [re] [textwrap] [functools] [pytest] [pkg_resources] [test_resources] 
classes: [FakeInstaller] 
functions: [strip_comments] [parse_distributions] [parametrize_test_working_set_resolve] [test_working_set_resolve] 

---
file name: folder/setuptools-45.2.0/pkg_resources/tests/data/my-test-package-source/setup.py 
(104 characters, 7 words)
import modules: [setuptools] 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/docs/conf.py 
(4422 characters, 363 words)
import modules: [subprocess] [sys] [os] 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/config.py 
(20575 characters, 1733 words)
import modules: [__future__] [io] [os] [sys] [warnings] [functools] [collections] [functools] [functools] [importlib] [distutils.errors] [setuptools.extern.packaging.version] [setuptools.extern.packaging.specifiers] [setuptools.extern.six] 
classes: [ConfigHandler] [ConfigMetadataHandler] [ConfigOptionsHandler] 
functions: [read_configuration] [_get_option] [configuration_to_dict] [parse_configuration] 

---
file name: folder/setuptools-45.2.0/setuptools/_deprecation_warning.py 
(218 characters, 25 words)
import modules: 
classes: [SetuptoolsDeprecationWarning] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/unicode_utils.py 
(996 characters, 99 words)
import modules: [unicodedata] [sys] [setuptools.extern] 
classes: 
functions: [decompose] [filesys_decode] [try_encode] 

---
file name: folder/setuptools-45.2.0/setuptools/dist.py 
(49864 characters, 4831 words)
import modules: [io] [sys] [re] [os] [warnings] [numbers] [distutils.log] [distutils.core] [distutils.cmd] [distutils.dist] [distutils.util] [distutils.debug] [distutils.fancy_getopt] [itertools] [collections] [email] [distutils.errors] [distutils.util] [distutils.version] [setuptools.extern] [setuptools.extern] [setuptools.extern] [setuptools.extern.six.moves] [None] [setuptools.depends] [setuptools] [setuptools.monkey] [setuptools.config] [pkg_resources] 
classes: [Distribution] [Feature] [DistDeprecationWarning] 
functions: [_get_unpatched] [get_metadata_version] [read_pkg_file] [write_pkg_file] [check_importable] [assert_string_list] [check_nsp] [check_extras] [_check_extra] [assert_bool] [check_requirements] [check_specifier] [check_entry_points] [check_test_suite] [check_package_data] [check_packages] 

---
file name: folder/setuptools-45.2.0/setuptools/extension.py 
(1729 characters, 187 words)
import modules: [re] [functools] [distutils.core] [distutils.errors] [distutils.extension] [setuptools.extern.six.moves] [monkey] 
classes: [Extension] [Library] 
functions: [_have_cython] 

---
file name: folder/setuptools-45.2.0/setuptools/version.py 
(144 characters, 11 words)
import modules: [pkg_resources] 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/_imp.py 
(2388 characters, 250 words)
import modules: [os] [importlib.util] [importlib.machinery] [py34compat] 
classes: 
functions: [find_spec] [find_module] [get_frozen_object] [get_module] 

---
file name: folder/setuptools-45.2.0/setuptools/installer.py 
(5336 characters, 483 words)
import modules: [glob] [os] [subprocess] [sys] [distutils] [distutils.errors] [pkg_resources] [setuptools.command.easy_install] [setuptools.extern] [setuptools.wheel] [py31compat] 
classes: 
functions: [_fixup_find_links] [_legacy_fetch_build_egg] [fetch_build_egg] [strip_marker] 

---
file name: folder/setuptools-45.2.0/setuptools/msvc.py 
(46807 characters, 4172 words)
import modules: [json] [io] [os] [os.path] [sys] [platform] [itertools] [distutils.errors] [setuptools.extern.packaging.version] [setuptools.extern.six.moves] [monkey] 
classes: [PlatformInfo] [RegistryInfo] [SystemInfo] [EnvironmentInfo] 
functions: [msvc9_find_vcvarsall] [msvc9_query_vcvarsall] [msvc14_get_vc_env] [msvc14_gen_lib_options] [_augment_exception] 

---
file name: folder/setuptools-45.2.0/setuptools/py34compat.py 
(245 characters, 18 words)
import modules: [importlib] 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/dep_util.py 
(949 characters, 105 words)
import modules: [distutils.dep_util] 
classes: 
functions: [newer_pairwise_group] 

---
file name: folder/setuptools-45.2.0/setuptools/package_index.py 
(40614 characters, 3816 words)
import modules: [sys] [os] [re] [shutil] [socket] [base64] [hashlib] [itertools] [warnings] [functools] [setuptools.extern] [setuptools.extern.six.moves] [setuptools] [pkg_resources] [setuptools] [distutils] [distutils.errors] [fnmatch] [setuptools.py27compat] [setuptools.py33compat] [setuptools.wheel] 
classes: [ContentChecker] [HashChecker] [PackageIndex] [Credential] [PyPIConfig] 
functions: [parse_requirement_arg] [parse_bdist_wininst] [egg_info_for_url] [distros_for_url] [distros_for_location] [distros_for_filename] [interpret_distro_name] [unique_everseen] [unique_values] [find_external_links] [decode_entity] [htmldecode] [socket_timeout] [_encode_auth] [open_with_auth] [_splituser] [fix_sf_url] [local_open] 

---
file name: folder/setuptools-45.2.0/setuptools/wheel.py 
(8468 characters, 625 words)
import modules: [distutils.util] [distutils] [email] [itertools] [os] [posixpath] [re] [zipfile] [pkg_resources] [setuptools] [pkg_resources] [setuptools.extern.packaging.tags] [setuptools.extern.packaging.utils] [setuptools.extern.six] [setuptools.command.egg_info] 
classes: [Wheel] 
functions: [unpack] 

---
file name: folder/setuptools-45.2.0/setuptools/monkey.py 
(5264 characters, 502 words)
import modules: [sys] [distutils.filelist] [platform] [types] [functools] [importlib] [inspect] [setuptools.extern] [setuptools] 
classes: 
functions: [_get_mro] [get_unpatched] [get_unpatched_class] [patch_all] [_patch_distribution_metadata] [patch_func] [get_unpatched_function] [patch_for_msvc_specialized_compiler] 

---
file name: folder/setuptools-45.2.0/setuptools/py27compat.py 
(1504 characters, 155 words)
import modules: [sys] [platform] [setuptools.extern] 
classes: 
functions: [get_all_headers] 

---
file name: folder/setuptools-45.2.0/setuptools/__init__.py 
(7273 characters, 749 words)
import modules: [os] [functools] [distutils.core] [distutils.filelist] [re] [distutils.errors] [distutils.util] [fnmatch] [_deprecation_warning] [setuptools.extern.six] [setuptools.extern.six.moves] [setuptools.version] [setuptools.extension] [setuptools.dist] [setuptools.depends] [None] 
classes: [PackageFinder] [PEP420PackageFinder] [Command] 
functions: [_install_setup_requires] [setup] [_find_all_simple] [findall] 

---
file name: folder/setuptools-45.2.0/setuptools/windows_support.py 
(714 characters, 60 words)
import modules: [platform] [ctypes] 
classes: 
functions: [windows_only] [hide_file] 

---
file name: folder/setuptools-45.2.0/setuptools/namespaces.py 
(3223 characters, 274 words)
import modules: [os] [distutils] [itertools] [setuptools.extern.six.moves] 
classes: [Installer] [DevelopInstaller] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/py33compat.py 
(1330 characters, 144 words)
import modules: [dis] [array] [collections] [setuptools.extern] [setuptools.extern.six.moves] 
classes: [Bytecode_compat] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/ssl_support.py 
(8543 characters, 779 words)
import modules: [os] [socket] [atexit] [re] [functools] [setuptools.extern.six.moves] [pkg_resources] 
classes: [VerifyingHTTPSHandler] [VerifyingHTTPSConn] 
functions: [opener_for] [once] [get_win_certfile] [find_ca_bundle] [_certifi_where] 

---
file name: folder/setuptools-45.2.0/setuptools/glob.py 
(5084 characters, 587 words)
import modules: [os] [re] [fnmatch] 
classes: 
functions: [glob] [iglob] [_iglob] [glob1] [glob0] [glob2] [_rlistdir] [has_magic] [_isrecursive] [escape] 

---
file name: folder/setuptools-45.2.0/setuptools/depends.py 
(5517 characters, 608 words)
import modules: [sys] [marshal] [contextlib] [distutils.version] [py33compat] [py27compat] [None] 
classes: [Require] 
functions: [maybe_close] [get_module_constant] [extract_constant] [_update_globals] 

---
file name: folder/setuptools-45.2.0/setuptools/build_meta.py 
(9960 characters, 883 words)
import modules: [io] [os] [sys] [tokenize] [shutil] [contextlib] [setuptools] [distutils] [setuptools.py31compat] [pkg_resources] [pkg_resources.py31compat] 
classes: [SetupRequirementsError] [Distribution] [_BuildMetaBackend] [_BuildMetaLegacyBackend] 
functions: [_to_str] [_get_immediate_subdirectories] [_file_with_extension] [_open_setup_script] 

---
file name: folder/setuptools-45.2.0/setuptools/archive_util.py 
(6626 characters, 646 words)
import modules: [zipfile] [tarfile] [os] [shutil] [posixpath] [contextlib] [distutils.errors] [pkg_resources] 
classes: [UnrecognizedFormat] 
functions: [default_filter] [unpack_archive] [unpack_directory] [unpack_zipfile] [unpack_tarfile] 

---
file name: folder/setuptools-45.2.0/setuptools/errors.py 
(524 characters, 63 words)
import modules: [distutils.errors] 
classes: [RemovedCommandError] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/site-patch.py 
(2346 characters, 264 words)
import modules: 
classes: 
functions: [__boot] 

---
file name: folder/setuptools-45.2.0/setuptools/sandbox.py 
(14284 characters, 1330 words)
import modules: [os] [sys] [tempfile] [operator] [functools] [itertools] [re] [contextlib] [pickle] [textwrap] [setuptools.extern] [setuptools.extern.six.moves] [pkg_resources.py31compat] [distutils.errors] [pkg_resources] 
classes: [UnpickleableException] [ExceptionSaver] [AbstractSandbox] [DirectorySandbox] [SandboxViolation] 
functions: [_execfile] [save_argv] [save_path] [override_temp] [pushd] [save_modules] [_clear_modules] [save_pkg_resources_state] [setup_context] [_needs_hiding] [hide_setuptools] [run_setup] 

---
file name: folder/setuptools-45.2.0/setuptools/py31compat.py 
(838 characters, 86 words)
import modules: 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/launch.py 
(787 characters, 92 words)
import modules: [tokenize] [sys] 
classes: 
functions: [run] 

---
file name: folder/setuptools-45.2.0/setuptools/lib2to3_ex.py 
(2013 characters, 153 words)
import modules: [distutils] [lib2to3.refactor] [setuptools] 
classes: [DistutilsRefactoringTool] [Mixin2to3] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/_vendor/ordered_set.py 
(15130 characters, 1729 words)
import modules: [collections] 
classes: [OrderedSet] 
functions: [is_iterable] 

---
file name: folder/setuptools-45.2.0/setuptools/_vendor/pyparsing.py 
(226313 characters, 22793 words)
import modules: [string] [copy] [sys] [warnings] [re] [sre_constants] [collections] [pprint] [traceback] [types] [datetime] 
classes: [_Constants] [ParseBaseException] [ParseException] [ParseFatalException] [ParseSyntaxException] [RecursiveGrammarException] [_ParseResultsWithOffset] [ParseResults] [ParserElement] [Token] [Empty] [NoMatch] [Literal] [Keyword] [CaselessLiteral] [CaselessKeyword] [CloseMatch] [Word] [Regex] [QuotedString] [CharsNotIn] [White] [_PositionToken] [GoToColumn] [LineStart] [LineEnd] [StringStart] [StringEnd] [WordStart] [WordEnd] [ParseExpression] [And] [Or] [MatchFirst] [Each] [ParseElementEnhance] [FollowedBy] [NotAny] [_MultipleMatch] [OneOrMore] [ZeroOrMore] [_NullToken] [Optional] [SkipTo] [Forward] [_ForwardNoRecurse] [TokenConverter] [Combine] [Group] [Dict] [Suppress] [OnlyOnce] [pyparsing_common] 
functions: [_xml_escape] [col] [lineno] [line] [_defaultStartDebugAction] [_defaultSuccessDebugAction] [_defaultExceptionDebugAction] [nullDebugAction] [_trim_arity] [traceParseAction] [delimitedList] [countedArray] [_flatten] [matchPreviousLiteral] [matchPreviousExpr] [_escapeRegexRangeChars] [oneOf] [dictOf] [originalTextFor] [ungroup] [locatedExpr] [srange] [matchOnlyAtCol] [replaceWith] [removeQuotes] [tokenMap] [_makeTags] [makeHTMLTags] [makeXMLTags] [withAttribute] [withClass] [infixNotation] [nestedExpr] [indentedBlock] [replaceHTMLEntity] 

---
file name: folder/setuptools-45.2.0/setuptools/_vendor/__init__.py 
(0 characters, 0 words)
import modules: 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/_vendor/six.py 
(30098 characters, 2532 words)
import modules: [__future__] [functools] [itertools] [operator] [sys] [types] 
classes: [_LazyDescr] [MovedModule] [_LazyModule] [MovedAttribute] [_SixMetaPathImporter] [_MovedItems] [Module_six_moves_urllib_parse] [Module_six_moves_urllib_error] [Module_six_moves_urllib_request] [Module_six_moves_urllib_response] [Module_six_moves_urllib_robotparser] [Module_six_moves_urllib] 
functions: [_add_doc] [_import_module] [add_move] [remove_move] [assertCountEqual] [assertRaisesRegex] [assertRegex] [with_metaclass] [add_metaclass] [python_2_unicode_compatible] 

---
file name: folder/setuptools-45.2.0/setuptools/_vendor/packaging/requirements.py 
(4742 characters, 479 words)
import modules: [__future__] [string] [re] [setuptools.extern.pyparsing] [setuptools.extern.pyparsing] [markers] [specifiers] 
classes: [InvalidRequirement] [Requirement] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/_vendor/packaging/version.py 
(11978 characters, 1296 words)
import modules: [__future__] [collections] [itertools] [re] [_structures] 
classes: [InvalidVersion] [_BaseVersion] [LegacyVersion] [Version] 
functions: [parse] [_parse_version_parts] [_legacy_cmpkey] [_parse_letter_version] [_parse_local_version] [_cmpkey] 

---
file name: folder/setuptools-45.2.0/setuptools/_vendor/packaging/__about__.py 
(744 characters, 93 words)
import modules: [__future__] 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/_vendor/packaging/_compat.py 
(865 characters, 123 words)
import modules: [__future__] [sys] 
classes: 
functions: [with_metaclass] 

---
file name: folder/setuptools-45.2.0/setuptools/_vendor/packaging/markers.py 
(8268 characters, 783 words)
import modules: [__future__] [operator] [os] [platform] [sys] [setuptools.extern.pyparsing] [setuptools.extern.pyparsing] [_compat] [specifiers] 
classes: [InvalidMarker] [UndefinedComparison] [UndefinedEnvironmentName] [Node] [Variable] [Value] [Op] [Marker] 
functions: [_coerce_parse_result] [_format_marker] [_eval_op] [_get_env] [_evaluate_markers] [format_full_version] [default_environment] 

---
file name: folder/setuptools-45.2.0/setuptools/_vendor/packaging/utils.py 
(1520 characters, 168 words)
import modules: [__future__] [re] [version] 
classes: 
functions: [canonicalize_name] [canonicalize_version] 

---
file name: folder/setuptools-45.2.0/setuptools/_vendor/packaging/__init__.py 
(562 characters, 65 words)
import modules: [__future__] [__about__] 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/_vendor/packaging/specifiers.py 
(27778 characters, 2933 words)
import modules: [__future__] [abc] [functools] [itertools] [re] [_compat] [version] 
classes: [InvalidSpecifier] [BaseSpecifier] [_IndividualSpecifier] [LegacySpecifier] [Specifier] [SpecifierSet] 
functions: [_require_version_compare] [_version_split] [_pad_version] 

---
file name: folder/setuptools-45.2.0/setuptools/_vendor/packaging/_structures.py 
(1416 characters, 140 words)
import modules: [__future__] 
classes: [Infinity] [NegativeInfinity] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/_vendor/packaging/tags.py 
(12933 characters, 1260 words)
import modules: [__future__] [distutils.util] [platform] [re] [sys] [sysconfig] [warnings] 
classes: [Tag] 
functions: [parse_tag] [_normalize_string] [_cpython_interpreter] [_cpython_abis] [_cpython_tags] [_pypy_interpreter] [_generic_abi] [_pypy_tags] [_generic_tags] [_py_interpreter_range] [_independent_tags] [_mac_arch] [_mac_binary_formats] [_mac_platforms] [_is_manylinux_compatible] [_glibc_version_string] [_check_glibc_version] [_have_compatible_glibc] [_linux_platforms] [_generic_platforms] [_interpreter_name] [_generic_interpreter] [sys_tags] 

---
file name: folder/setuptools-45.2.0/setuptools/command/build_clib.py 
(4415 characters, 406 words)
import modules: [distutils.errors] [distutils] [setuptools.dep_util] 
classes: [build_clib] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/install_egg_info.py 
(2203 characters, 183 words)
import modules: [distutils] [os] [setuptools] [setuptools] [setuptools.archive_util] [pkg_resources] 
classes: [install_egg_info] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/py36compat.py 
(4994 characters, 386 words)
import modules: [os] [glob] [distutils.util] [distutils.command] [setuptools.extern.six.moves] 
classes: [sdist_add_defaults] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/dist_info.py 
(960 characters, 77 words)
import modules: [os] [distutils.core] [distutils] 
classes: [dist_info] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/build_py.py 
(9596 characters, 830 words)
import modules: [glob] [distutils.util] [os] [fnmatch] [textwrap] [io] [distutils.errors] [itertools] [setuptools.extern] [setuptools.extern.six.moves] 
classes: [build_py] 
functions: [_unique_everseen] [assert_relative] 

---
file name: folder/setuptools-45.2.0/setuptools/command/upload_docs.py 
(7314 characters, 633 words)
import modules: [base64] [distutils] [distutils.errors] [os] [socket] [zipfile] [tempfile] [shutil] [itertools] [functools] [setuptools.extern] [setuptools.extern.six.moves] [pkg_resources] [upload] 
classes: [upload_docs] 
functions: [_encode] 

---
file name: folder/setuptools-45.2.0/setuptools/command/alias.py 
(2426 characters, 230 words)
import modules: [distutils.errors] [setuptools.extern.six.moves] [setuptools.command.setopt] 
classes: [alias] 
functions: [shquote] [format_alias] 

---
file name: folder/setuptools-45.2.0/setuptools/command/egg_info.py 
(25548 characters, 2408 words)
import modules: [distutils.errors] [distutils.util] [distutils] [distutils.errors] [distutils.filelist] [os] [re] [sys] [io] [warnings] [time] [collections] [setuptools.extern] [setuptools.extern.six.moves] [setuptools] [setuptools.command.sdist] [setuptools.command.sdist] [setuptools.command.setopt] [setuptools.command] [pkg_resources] [setuptools.glob] [setuptools.extern] [setuptools] 
classes: [InfoCommon] [egg_info] [FileList] [manifest_maker] [EggInfoDeprecationWarning] 
functions: [translate_pattern] [write_file] [write_pkg_info] [warn_depends_obsolete] [_write_requirements] [write_requirements] [write_setup_requirements] [write_toplevel_names] [overwrite_arg] [write_arg] [write_entries] [get_pkg_info_revision] 

---
file name: folder/setuptools-45.2.0/setuptools/command/bdist_wininst.py 
(637 characters, 44 words)
import modules: 
classes: [bdist_wininst] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/test.py 
(9623 characters, 791 words)
import modules: [os] [operator] [sys] [contextlib] [itertools] [unittest] [distutils.errors] [distutils] [unittest] [setuptools.extern] [setuptools.extern.six.moves] [pkg_resources] [setuptools] [build_py] 
classes: [ScanningLoader] [NonDataProperty] [test] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/sdist.py 
(8092 characters, 701 words)
import modules: [distutils] [os] [sys] [io] [contextlib] [setuptools.extern] [py36compat] [pkg_resources] 
classes: [sdist] 
functions: [walk_revctrl] 

---
file name: folder/setuptools-45.2.0/setuptools/command/upload.py 
(462 characters, 50 words)
import modules: [distutils] [setuptools.errors] 
classes: [upload] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/__init__.py 
(568 characters, 50 words)
import modules: [distutils.command.bdist] [sys] [setuptools.command] 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/develop.py 
(8188 characters, 655 words)
import modules: [distutils.util] [distutils] [distutils.errors] [os] [glob] [io] [setuptools.extern] [pkg_resources] [setuptools.command.easy_install] [setuptools] [setuptools] 
classes: [develop] [VersionlessRequirement] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/install_scripts.py 
(2519 characters, 209 words)
import modules: [distutils] [os] [sys] [pkg_resources] 
classes: [install_scripts] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/saveopts.py 
(658 characters, 65 words)
import modules: [setuptools.command.setopt] 
classes: [saveopts] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/rotate.py 
(2164 characters, 195 words)
import modules: [distutils.util] [distutils] [distutils.errors] [os] [shutil] [setuptools.extern] [setuptools] 
classes: [rotate] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/setopt.py 
(5085 characters, 462 words)
import modules: [distutils.util] [distutils] [distutils.errors] [distutils] [os] [setuptools.extern.six.moves] [setuptools] 
classes: [option_base] [setopt] 
functions: [config_file] [edit_config] 

---
file name: folder/setuptools-45.2.0/setuptools/command/bdist_egg.py 
(18185 characters, 1571 words)
import modules: [distutils.errors] [distutils.dir_util] [distutils] [types] [sys] [os] [re] [textwrap] [marshal] [setuptools.extern] [pkg_resources] [pkg_resources] [setuptools.extension] [setuptools] 
classes: [bdist_egg] 
functions: [strip_module] [sorted_walk] [write_stub] [walk_egg] [analyze_egg] [write_safety_flag] [scan_module] [iter_symbols] [can_scan] [make_zipfile] 

---
file name: folder/setuptools-45.2.0/setuptools/command/build_ext.py 
(13048 characters, 1060 words)
import modules: [os] [sys] [itertools] [distutils.file_util] [distutils.ccompiler] [distutils.sysconfig] [distutils.errors] [distutils] [setuptools.extension] [setuptools.extern] 
classes: [build_ext] 
functions: [_customize_compiler_for_shlib] [if_dl] [get_abi3_suffix] 

---
file name: folder/setuptools-45.2.0/setuptools/command/install_lib.py 
(3875 characters, 347 words)
import modules: [os] [sys] [itertools] 
classes: [install_lib] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/install.py 
(4705 characters, 427 words)
import modules: [distutils.errors] [inspect] [glob] [warnings] [platform] [setuptools] 
classes: [install] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/bdist_rpm.py 
(1508 characters, 134 words)
import modules: 
classes: [bdist_rpm] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/register.py 
(468 characters, 48 words)
import modules: [distutils] [setuptools.errors] 
classes: [register] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/command/easy_install.py 
(87501 characters, 7863 words)
import modules: [glob] [distutils.util] [distutils.util] [distutils.errors] [distutils.command.install] [distutils] [distutils.command.build_scripts] [distutils.spawn] [sys] [os] [zipimport] [shutil] [tempfile] [zipfile] [re] [stat] [random] [textwrap] [warnings] [site] [struct] [contextlib] [subprocess] [shlex] [io] [sysconfig] [setuptools] [setuptools.extern] [setuptools.extern.six.moves] [setuptools] [setuptools.sandbox] [setuptools.py27compat] [setuptools.command] [setuptools.archive_util] [setuptools.package_index] [setuptools.command] [setuptools.wheel] [pkg_resources] [pkg_resources.py31compat] 
classes: [easy_install] [PthDistributions] [RewritePthDistributions] [CommandSpec] [WindowsCommandSpec] [ScriptWriter] [WindowsScriptWriter] [WindowsExecutableLauncherWriter] [EasyInstallDeprecationWarning] 
functions: [is_64bit] [samefile] [_one_liner] [_pythonpath] [get_site_dirs] [expand_paths] [extract_wininst_cfg] [get_exe_prefixes] [_first_line_re] [auto_chmod] [update_dist_caches] [_collect_zipimporter_cache_entries] [_update_zipimporter_cache] [_uncache] [_remove_and_clear_zip_directory_cache_data] [is_python] [is_sh] [nt_quote_arg] [is_python_script] [chmod] [get_win_launcher] [load_launcher_manifest] [rmtree] [current_umask] [bootstrap] [main] [_patch_usage] 

---
file name: folder/setuptools-45.2.0/setuptools/extern/__init__.py 
(2514 characters, 246 words)
import modules: [sys] 
classes: [VendorImporter] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_setopt.py 
(1101 characters, 86 words)
import modules: [__future__] [io] [six] [setuptools.command] [setuptools.extern.six.moves] 
classes: [TestEdit] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_test.py 
(4627 characters, 410 words)
import modules: [__future__] [mock] [distutils] [os] [pytest] [setuptools.command.test] [setuptools.dist] [textwrap] 
classes: 
functions: [sample_test] [quiet_log] [test_test] [test_tests_are_run_once] [test_warns_deprecation] [test_deprecation_stderr] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_develop.py 
(6062 characters, 511 words)
import modules: [__future__] [os] [site] [sys] [io] [subprocess] [platform] [setuptools.extern] [setuptools.command] [pytest] [setuptools.command.develop] [setuptools.dist] [None] [None] 
classes: [TestDevelop] [TestResolver] [TestNamespaces] 
functions: [temp_user] [test_env] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/files.py 
(1124 characters, 107 words)
import modules: [os] [pkg_resources.py31compat] 
classes: 
functions: [build_files] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_build_ext.py 
(3193 characters, 255 words)
import modules: [sys] [distutils.sysconfig] [setuptools.extern] [setuptools.command.build_ext] [setuptools.dist] [setuptools.extension] [None] [files] [textwrap] 
classes: [TestBuildExt] 
functions: [test_build_ext_config_handling] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/textwrap.py 
(138 characters, 13 words)
import modules: [__future__] [textwrap] 
classes: 
functions: [DALS] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/fixtures.py 
(583 characters, 45 words)
import modules: [pytest] [None] 
classes: 
functions: [user_override] [tmpdir_cwd] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_sandbox.py 
(4249 characters, 306 words)
import modules: [os] [types] [pytest] [pkg_resources] [setuptools.sandbox] 
classes: [TestSandbox] [TestExceptionSaver] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_glob.py 
(765 characters, 64 words)
import modules: [pytest] [setuptools.glob] [files] 
classes: 
functions: [test_glob] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_wheel.py 
(15632 characters, 956 words)
import modules: [distutils.sysconfig] [distutils.util] [contextlib] [glob] [inspect] [os] [shutil] [subprocess] [sys] [zipfile] [pytest] [pkg_resources] [setuptools.extern.packaging.utils] [setuptools.extern.packaging.tags] [setuptools.wheel] [contexts] [files] [textwrap] 
classes: [Record] 
functions: [test_wheel_info] [build_wheel] [tree_set] [flatten_tree] [format_install_tree] [_check_wheel_install] [test_wheel_install] [test_wheel_install_pep_503] [test_wheel_no_dist_dir] [test_wheel_is_compatible] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/server.py 
(2601 characters, 222 words)
import modules: [os] [time] [threading] [setuptools.extern.six.moves] [setuptools.extern.six.moves.urllib_parse] [setuptools.extern.six.moves.urllib.request] 
classes: [IndexServer] [RequestRecorder] [MockServer] 
functions: [path_to_url] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/contexts.py 
(2141 characters, 197 words)
import modules: [tempfile] [os] [shutil] [sys] [contextlib] [site] [setuptools.extern] [pkg_resources] 
classes: 
functions: [tempdir] [environment] [quiet] [save_user_site_setting] [save_pkg_resources_state] [suppress_exceptions] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_bdist_egg.py 
(1800 characters, 138 words)
import modules: [os] [re] [zipfile] [pytest] [setuptools.dist] [None] 
classes: [Test] 
functions: [setup_context] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/script-with-bom.py 
(46 characters, 8 words)
import modules: 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_upload.py 
(552 characters, 50 words)
import modules: [setuptools.command.upload] [setuptools.dist] [setuptools.errors] [pytest] 
classes: [TestUpload] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/text.py 
(190 characters, 20 words)
import modules: [__future__] 
classes: [Filenames] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_dist_info.py 
(2316 characters, 176 words)
import modules: [__future__] [setuptools.extern.six.moves] [pytest] [pkg_resources] [textwrap] 
classes: [TestDistInfo] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_namespaces.py 
(4616 characters, 355 words)
import modules: [__future__] [sys] [subprocess] [pytest] [None] [setuptools.command] 
classes: [TestNamespaces] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_manifest.py 
(18109 characters, 1362 words)
import modules: [contextlib] [os] [shutil] [sys] [tempfile] [itertools] [distutils] [distutils.errors] [pkg_resources.py31compat] [setuptools.command.egg_info] [setuptools.dist] [setuptools.extern] [setuptools.tests.textwrap] [pytest] 
classes: [TempDirTestCase] [TestManifestTest] [TestFileListTest] 
functions: [make_local_path] [quiet] [touch] [pattern_match] [pattern_mismatch] [test_translated_pattern_match] [test_translated_pattern_mismatch] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_sdist.py 
(15749 characters, 1409 words)
import modules: [__future__] [os] [sys] [tempfile] [unicodedata] [contextlib] [io] [setuptools.extern] [setuptools.extern.six.moves] [pytest] [pkg_resources] [setuptools.command.sdist] [setuptools.command.egg_info] [setuptools.dist] [setuptools.tests] [text] [None] 
classes: [TestSdistTest] 
functions: [quiet] [posix] [decompose] [read_all_bytes] [latin1_fail] [touch] [test_default_revctrl] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_integration.py 
(5541 characters, 443 words)
import modules: [glob] [os] [sys] [re] [subprocess] [functools] [tarfile] [zipfile] [setuptools.extern.six.moves] [pytest] [setuptools.command.easy_install] [setuptools.dist] 
classes: 
functions: [setup_module] [install_context] [_install_one] [test_stevedore] [test_virtualenvwrapper] [test_pbr] [test_python_novaclient] [test_pyuri] [test_build_deps_on_distutils] [install] [download_and_extract] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/__init__.py 
(430 characters, 49 words)
import modules: [locale] [pytest] [setuptools.extern.six] 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_setuptools.py 
(12732 characters, 921 words)
import modules: [sys] [os] [distutils.core] [distutils.cmd] [distutils.errors] [distutils.errors] [distutils.core] [distutils.version] [pytest] [setuptools] [setuptools.dist] [setuptools] [setuptools.depends] [setuptools.extern] 
classes: [TestDepends] [TestDistro] [TestFeatures] [TestCommandTests] 
functions: [makeSetup] [example_source] [test_findall] [test_findall_curdir] [can_symlink] [test_findall_missing_symlink] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/mod_with_constant.py 
(22 characters, 4 words)
import modules: 
classes: 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_find_packages.py 
(6443 characters, 451 words)
import modules: [os] [sys] [shutil] [tempfile] [platform] [pytest] [None] [setuptools.extern.six] [setuptools] 
classes: [TestFindPackages] 
functions: [can_symlink] [has_symlink] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_windows_wrappers.py 
(6239 characters, 619 words)
import modules: [__future__] [sys] [textwrap] [subprocess] [pytest] [setuptools.command.easy_install] [pkg_resources] 
classes: [WrapperTester] [TestCLI] [TestGUI] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_egg_info.py 
(32549 characters, 2134 words)
import modules: [sys] [ast] [os] [glob] [re] [stat] [time] [setuptools.command.egg_info] [setuptools.dist] [setuptools.extern.six.moves] [pytest] [None] [files] [textwrap] [None] 
classes: [Environment] [TestEggInfo] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/namespaces.py 
(1376 characters, 114 words)
import modules: [__future__] [textwrap] 
classes: 
functions: [build_namespace_package] [make_site_dir] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_install_scripts.py 
(3391 characters, 280 words)
import modules: [io] [sys] [pytest] [setuptools.command.install_scripts] [setuptools.dist] [None] 
classes: [TestInstallScripts] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_dep_util.py 
(977 characters, 87 words)
import modules: [setuptools.dep_util] [os] [pytest] 
classes: 
functions: [groups_target] [test_newer_pairwise_group] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_register.py 
(562 characters, 50 words)
import modules: [setuptools.command.register] [setuptools.dist] [setuptools.errors] [pytest] 
classes: [TestRegister] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_unicode_utils.py 
(316 characters, 22 words)
import modules: [setuptools] 
classes: 
functions: [test_filesys_decode_fs_encoding_is_None] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_packageindex.py 
(11562 characters, 909 words)
import modules: [__future__] [sys] [os] [distutils.errors] [setuptools.extern] [setuptools.extern.six.moves] [mock] [pytest] [pkg_resources] [setuptools.package_index] [setuptools.tests.server] [textwrap] 
classes: [TestPackageIndex] [TestContentCheckers] [TestPyPIConfig] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_msvc.py 
(5898 characters, 481 words)
import modules: [os] [contextlib] [distutils.errors] [mock] [pytest] [None] 
classes: [TestModulePatch] 
functions: [mock_reg] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_upload_docs.py 
(1779 characters, 154 words)
import modules: [os] [zipfile] [contextlib] [pytest] [setuptools.command.upload_docs] [setuptools.dist] [textwrap] [None] 
classes: [TestUploadDocsTest] 
functions: [sample_project] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_archive_util.py 
(975 characters, 91 words)
import modules: [tarfile] [io] [setuptools.extern] [pytest] [setuptools] 
classes: 
functions: [tarfile_with_unicode] [test_unicode_files] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_depends.py 
(425 characters, 38 words)
import modules: [sys] [setuptools] 
classes: [TestGetModuleConstant] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_build_py.py 
(525 characters, 41 words)
import modules: [os] [setuptools.dist] 
classes: 
functions: [test_directories_in_package_data_glob] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_config.py 
(28002 characters, 2044 words)
import modules: [__future__] [contextlib] [pytest] [distutils.errors] [mock] [setuptools.dist] [setuptools.config] [setuptools.extern.six.moves] [None] [textwrap] 
classes: [ErrConfigHandler] [TestConfigurationReader] [TestMetadata] [TestOptions] [TestExternalSetters] 
functions: [make_package_dir] [fake_env] [get_dist] [test_parsers_implemented] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_dist.py 
(10718 characters, 852 words)
import modules: [__future__] [io] [collections] [re] [distutils.errors] [setuptools.dist] [setuptools] [setuptools.extern.six.moves.urllib.request] [setuptools.extern.six.moves.urllib_parse] [setuptools.extern] [textwrap] [test_easy_install] [pytest] 
classes: 
functions: [test_dist_fetch_build_egg] [test_dist__get_unpatched_deprecated] [__read_test_cases] [test_read_metadata] [__maintainer_test_cases] [test_maintainer_author] [test_provides_extras_deterministic_order] [test_check_package_data] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_build_clib.py 
(2117 characters, 176 words)
import modules: [pytest] [mock] [distutils.errors] [setuptools.command.build_clib] [setuptools.dist] 
classes: [TestBuildCLib] 
functions: 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_virtualenv.py 
(6485 characters, 531 words)
import modules: [glob] [os] [sys] [pytest] [pytest] [pytest_fixture_config] [pytest_virtualenv] [textwrap] [test_easy_install] 
classes: 
functions: [disable_requires_python] [pytest_virtualenv_works] [bare_virtualenv] [test_clean_env_install] [_get_pip_versions] [test_pip_upgrade_from_source] [_check_test_command_install_requirements] [test_test_command_install_requirements] [test_test_command_install_requirements_when_using_easy_install] [test_no_missing_dependencies] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_easy_install.py 
(40533 characters, 2714 words)
import modules: [__future__] [sys] [os] [tempfile] [site] [contextlib] [tarfile] [logging] [itertools] [distutils.errors] [io] [zipfile] [mock] [time] [setuptools.extern] [pytest] [setuptools] [setuptools.sandbox] [setuptools.command.easy_install] [setuptools.dist] [pkg_resources] [setuptools.tests.server] [setuptools.tests] [pkg_resources] [None] [files] [textwrap] 
classes: [FakeDist] [TestEasyInstallTest] [TestPTHFileWriter] [TestUserInstallTest] [TestDistutilsPackage] [TestSetupRequires] [TestScriptHeader] [TestCommandSpec] [TestWindowsScriptWriter] 
functions: [setup_context] [distutils_package] [mock_index] [make_trivial_sdist] [make_nspkg_sdist] [make_python_requires_sdist] [make_sdist] [create_setup_requires_package] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/environment.py 
(1703 characters, 180 words)
import modules: [os] [sys] [unicodedata] 
classes: 
functions: [_which_dirs] [run_setup_py] 

---
file name: folder/setuptools-45.2.0/setuptools/tests/test_build_meta.py 
(14587 characters, 958 words)
import modules: [__future__] [os] [shutil] [tarfile] [pytest] [files] [textwrap] [None] [importlib] [concurrent] 
classes: [BuildBackendBase] [BuildBackend] [BuildBackendCaller] [TestBuildMetaBackend] [TestBuildMetaLegacyBackend] 
functions: 