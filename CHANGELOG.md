# Changelog

## [3.0.0](https://github.com/luckdev2350/auth-js/compare/v2.68.0...v3.0.0) (2025-01-28)


### ⚠ BREAKING CHANGES

* Release V2

### Features

* `_recoverAndRefresh` does not remove session on retryable error ([#710](https://github.com/luckdev2350/auth-js/issues/710)) ([add762e](https://github.com/luckdev2350/auth-js/commit/add762e31b37c4b6b7f8bac98fa674ff01015be0))
* `navigatorLock` check for spec compatibility ([#761](https://github.com/luckdev2350/auth-js/issues/761)) ([8de722f](https://github.com/luckdev2350/auth-js/commit/8de722f2d1d2771aa0853a48fce1393175c74c2e))
* acquire lock around visibility change callback ([#764](https://github.com/luckdev2350/auth-js/issues/764)) ([a86f07d](https://github.com/luckdev2350/auth-js/commit/a86f07dc090cae5d5e80f2295d14a0a7d3a70b2e))
* acquire locks around mfa methods ([#788](https://github.com/luckdev2350/auth-js/issues/788)) ([4b6ec58](https://github.com/luckdev2350/auth-js/commit/4b6ec587f3011e6ef9c9ed1510050688410bd8f0))
* add _acquireLock and navigatorLock ([#736](https://github.com/luckdev2350/auth-js/issues/736)) ([406e95e](https://github.com/luckdev2350/auth-js/commit/406e95e4378d76aeb8d29ae6e75d18b3118e2790))
* Add 'kakao' to Provider type ([#720](https://github.com/luckdev2350/auth-js/issues/720)) ([ef16123](https://github.com/luckdev2350/auth-js/commit/ef161237b5fba464657d692a39120f944ca173fa))
* add `AuthWeakPasswordError` ([#817](https://github.com/luckdev2350/auth-js/issues/817)) ([abff667](https://github.com/luckdev2350/auth-js/commit/abff667215ce0a06dd45abb07fbb0cc3759fafa5))
* add `setSession` support for a SSR context ([be413ca](https://github.com/luckdev2350/auth-js/commit/be413caa0db084afc39eae0af7508d6649117dd3))
* add `signInWithSSO` method as `[@experimental](https://github.com/experimental)` ([#526](https://github.com/luckdev2350/auth-js/issues/526)) ([a441eef](https://github.com/luckdev2350/auth-js/commit/a441eef4d7291ec20b756cde99ccee87329594d0))
* add `signOut()` scope option ([#713](https://github.com/luckdev2350/auth-js/issues/713)) ([0f04bfc](https://github.com/luckdev2350/auth-js/commit/0f04bfc30e9cdd841ec723448142d8e0dcb63709))
* add `skipBrowserRedirect` option to `signInWithOAuth` ([#575](https://github.com/luckdev2350/auth-js/issues/575)) ([11a0fbc](https://github.com/luckdev2350/auth-js/commit/11a0fbc406b03ffd31304bf64a3033b8ca8de223)), closes [#417](https://github.com/luckdev2350/auth-js/issues/417)
* add async/await support for `onAuthStateChange` callbacks ([#685](https://github.com/luckdev2350/auth-js/issues/685)) ([8aaa6ac](https://github.com/luckdev2350/auth-js/commit/8aaa6ac087f46b02fb552f9a154885fc65dca7ef)), closes [#276](https://github.com/luckdev2350/auth-js/issues/276)
* add bindings for Multi-Factor Authentication (Phone) ([#932](https://github.com/luckdev2350/auth-js/issues/932)) ([b957c30](https://github.com/luckdev2350/auth-js/commit/b957c30782065e4cc421a526c62c101d35c443d4))
* add challengeAndVerify ([711fcd5](https://github.com/luckdev2350/auth-js/commit/711fcd51d511b031bdeee5ea2d45bcbbdfb59b67))
* add debug messages and configuration ([#712](https://github.com/luckdev2350/auth-js/issues/712)) ([c990bc2](https://github.com/luckdev2350/auth-js/commit/c990bc23f08f56e34502b4fc62334da96bd3ca3b))
* add enhanced `localStorage` support check ([#600](https://github.com/luckdev2350/auth-js/issues/600)) ([1ee7231](https://github.com/luckdev2350/auth-js/commit/1ee72310cf165d99a5a0c533e7d2f8d539f0413f))
* add experimental `signInWithIdToken` for Apple, Google ([#603](https://github.com/luckdev2350/auth-js/issues/603)) ([1763d48](https://github.com/luckdev2350/auth-js/commit/1763d48d979889da44287ce07ff781b2e7b83b30))
* add getAMR and getAAL ([fa38a48](https://github.com/luckdev2350/auth-js/commit/fa38a481dfc23484bdfecd78ad2f7d5c6c00904a))
* add identity linking methods ([#814](https://github.com/luckdev2350/auth-js/issues/814)) ([46d0f87](https://github.com/luckdev2350/auth-js/commit/46d0f873172188406d113e9d76c1cda28cf0b12b))
* add kakao to sign in with ID token ([#845](https://github.com/luckdev2350/auth-js/issues/845)) ([e2337ba](https://github.com/luckdev2350/auth-js/commit/e2337bad535598d9f751505de52a18c59f1505c3))
* add linkedin oidc type ([#796](https://github.com/luckdev2350/auth-js/issues/796)) ([58a1ee6](https://github.com/luckdev2350/auth-js/commit/58a1ee69b566987052596e269ee8a3eef477dc2e))
* add method for anonymous sign-in ([#858](https://github.com/luckdev2350/auth-js/issues/858)) ([e8a1fc9](https://github.com/luckdev2350/auth-js/commit/e8a1fc9a40947b949080107138eade09f06f5868))
* add more method implementations ([d8c5234](https://github.com/luckdev2350/auth-js/commit/d8c5234edddb6302e561bcfb9975f4225ca0c3ad))
* add multi-tab state change notifications ([#566](https://github.com/luckdev2350/auth-js/issues/566)) ([0b6c5db](https://github.com/luckdev2350/auth-js/commit/0b6c5db2cf9656312b8d42b1085cd33836ad4dce))
* add new auto refresh token algorithm ([#564](https://github.com/luckdev2350/auth-js/issues/564)) ([013afae](https://github.com/luckdev2350/auth-js/commit/013afaeb45e5d964a8cca467b748a3daa557f22c))
* add pkce ([#591](https://github.com/luckdev2350/auth-js/issues/591)) ([2fc2781](https://github.com/luckdev2350/auth-js/commit/2fc278106c1b2b4f4d45d75c9ad3f02588af1cbe))
* add pkce magic link bindings ([#656](https://github.com/luckdev2350/auth-js/issues/656)) ([e986754](https://github.com/luckdev2350/auth-js/commit/e98675400570aa900cd3c9274bce046a0eedcc98))
* add pkce option to signup ([#661](https://github.com/luckdev2350/auth-js/issues/661)) ([eb96536](https://github.com/luckdev2350/auth-js/commit/eb96536a441d21fae75d25ab6de346808c6e6044))
* add process lock for optional use in non-browser environments (React Native) ([#977](https://github.com/luckdev2350/auth-js/issues/977)) ([8af88b6](https://github.com/luckdev2350/auth-js/commit/8af88b6f4e41872b73e84c40f71793dab6c62126))
* add provider refresh token ([7c310ea](https://github.com/luckdev2350/auth-js/commit/7c310ea06aaf820091ba819477fce916f640186e))
* add resend method ([#631](https://github.com/luckdev2350/auth-js/issues/631)) ([1ffdd5c](https://github.com/luckdev2350/auth-js/commit/1ffdd5cc44b027ef6cfa87a175bfe19dafa0c88b))
* add SSO PKCE ([#707](https://github.com/luckdev2350/auth-js/issues/707)) ([ba66b4d](https://github.com/luckdev2350/auth-js/commit/ba66b4d366e6c7d4428c06f75badb627120b7414))
* add support for error codes ([#855](https://github.com/luckdev2350/auth-js/issues/855)) ([99821f4](https://github.com/luckdev2350/auth-js/commit/99821f4a1f6fdb3a222cd0f660210016e6cc823e))
* add updateUser (email_change) bindings for pkce  ([#665](https://github.com/luckdev2350/auth-js/issues/665)) ([5ceb216](https://github.com/luckdev2350/auth-js/commit/5ceb21655358088ebe463440262afd1ff7791c06))
* allow customizing the debug log function ([#785](https://github.com/luckdev2350/auth-js/issues/785)) ([1f41e5d](https://github.com/luckdev2350/auth-js/commit/1f41e5d365ae843d19e729c0747a1a95fc1d22c4))
* bump typescript target to ES2017 ([#729](https://github.com/luckdev2350/auth-js/issues/729)) ([92b47d2](https://github.com/luckdev2350/auth-js/commit/92b47d29bf74bc97f8a14c891d2b932f797518f8))
* call `SIGNED_OUT` event if token refresh fails ([#815](https://github.com/luckdev2350/auth-js/issues/815)) ([a0ff059](https://github.com/luckdev2350/auth-js/commit/a0ff05915ea1f68aa6d4e7da9533285ca3d80eff))
* change location of evaluation ([#703](https://github.com/luckdev2350/auth-js/issues/703)) ([abd3339](https://github.com/luckdev2350/auth-js/commit/abd33391f00a647bd749adedcd618832a1a1275c))
* complete OIDC support for Apple, Google and others ([#690](https://github.com/luckdev2350/auth-js/issues/690)) ([6d0fd5f](https://github.com/luckdev2350/auth-js/commit/6d0fd5f517cfcb1d7fa0ff53fde246bce1bd0b0c))
* consider session expired with margin on getSession() without auto refresh ([#1027](https://github.com/luckdev2350/auth-js/issues/1027)) ([80f88e4](https://github.com/luckdev2350/auth-js/commit/80f88e4bd2809db765a8d103954e827d8473b7db))
* default to `navigatorLock` on browsers ([#807](https://github.com/luckdev2350/auth-js/issues/807)) ([b717b1c](https://github.com/luckdev2350/auth-js/commit/b717b1cd9466ddc067aa0a5fad0d9e046e3782d4))
* disallow setSession loophole ([#536](https://github.com/luckdev2350/auth-js/issues/536)) ([21e496c](https://github.com/luckdev2350/auth-js/commit/21e496cf6662d29162936a8641b4b29b8144b194)), closes [#490](https://github.com/luckdev2350/auth-js/issues/490)
* dont fire `SIGNED_IN` event on `PASSWORD_RECOVERY` ([#629](https://github.com/luckdev2350/auth-js/issues/629)) ([6bc45dc](https://github.com/luckdev2350/auth-js/commit/6bc45dce8ed0332d55271eef1a693738f69d9e2d))
* drop window prefix ([#660](https://github.com/luckdev2350/auth-js/issues/660)) ([cf37d70](https://github.com/luckdev2350/auth-js/commit/cf37d70bc516d31f7a2cea0365782936239b7923))
* explicit `cache: no-store` in fetch ([#847](https://github.com/luckdev2350/auth-js/issues/847)) ([034bee0](https://github.com/luckdev2350/auth-js/commit/034bee09c3f0a4613d9a3e7bd3bc5f70682f5a66))
* fix stack guard issues with Safari ([#743](https://github.com/luckdev2350/auth-js/issues/743)) ([c614101](https://github.com/luckdev2350/auth-js/commit/c6141010e0589bec1466e8eacb3b19f956d47dce))
* increase auto refresh tick duration to 30s from 10s ([#651](https://github.com/luckdev2350/auth-js/issues/651)) ([c7eb42f](https://github.com/luckdev2350/auth-js/commit/c7eb42fc048023baa733de75137c7ff303a6b8d4))
* initial MFA stubs ([358e602](https://github.com/luckdev2350/auth-js/commit/358e6026241d382ce17021633cef1a1cefb13f76))
* invoke callback on onAuthStateChange ([#627](https://github.com/luckdev2350/auth-js/issues/627)) ([832d168](https://github.com/luckdev2350/auth-js/commit/832d1680099bfcd2fe7886331a006d2b8220e2f5))
* keep expired session on initialization ([#598](https://github.com/luckdev2350/auth-js/issues/598)) ([1a63a42](https://github.com/luckdev2350/auth-js/commit/1a63a4289bd769f26dd774ff8a9aaafb8e8a5a63))
* make certain properties in `UserIdentity` nullable ([#619](https://github.com/luckdev2350/auth-js/issues/619)) ([fc4fce4](https://github.com/luckdev2350/auth-js/commit/fc4fce468c0809e7e7bba4568b516e7cf8f0e48b))
* Merge pull request [#304](https://github.com/luckdev2350/auth-js/issues/304) from supabase/km/refactor-sign-in ([f14cc9f](https://github.com/luckdev2350/auth-js/commit/f14cc9f69994abfd24e2c168062f4fee5a8e1121))
* no persist of session with no changes in `_recoverAndRefresh` ([#711](https://github.com/luckdev2350/auth-js/issues/711)) ([964f2fd](https://github.com/luckdev2350/auth-js/commit/964f2fd661d01e2b55341c2ddb0001c2e5593048))
* parse `expires_at` if present ([#735](https://github.com/luckdev2350/auth-js/issues/735)) ([49e7df4](https://github.com/luckdev2350/auth-js/commit/49e7df417d9e095084b72745042f61bc6001a438))
* pkce challenge support in React Native with Segment ([#772](https://github.com/luckdev2350/auth-js/issues/772)) ([b4494cb](https://github.com/luckdev2350/auth-js/commit/b4494cb463bb73b985acb8fa805d07f3fb68f490))
* pop implicit flow URL from back stack ([#574](https://github.com/luckdev2350/auth-js/issues/574)) ([dfdf76c](https://github.com/luckdev2350/auth-js/commit/dfdf76c8f287b10313bb36d535f863fc1990926f))
* provide default storage when `persistSession` is false or `localStorage` is not supported ([#774](https://github.com/luckdev2350/auth-js/issues/774)) ([9324fa5](https://github.com/luckdev2350/auth-js/commit/9324fa5d593edf9c26cfcbea61221c97ec75f376))
* refactor `_getSessionFromURL` to be easier to read ([#733](https://github.com/luckdev2350/auth-js/issues/733)) ([86eb5b2](https://github.com/luckdev2350/auth-js/commit/86eb5b2de821c93ad76757e4a7107cb605f65118))
* refactor `_handleRequest` ([#708](https://github.com/luckdev2350/auth-js/issues/708)) ([65f1c52](https://github.com/luckdev2350/auth-js/commit/65f1c52e921d577f408f435ec8377c9fafa1a90b))
* refactor `signInWithSSO` types to work with docs ([#644](https://github.com/luckdev2350/auth-js/issues/644)) ([85ac7d8](https://github.com/luckdev2350/auth-js/commit/85ac7d886dfbf2cfec55ce726df782b1223a53d9))
* refactor returns types to always return data ([0b3086a](https://github.com/luckdev2350/auth-js/commit/0b3086ab851424317c6b88a9e6498615cdf67279))
* refactor to `_useSession` semantics ([#726](https://github.com/luckdev2350/auth-js/issues/726)) ([ce5ae82](https://github.com/luckdev2350/auth-js/commit/ce5ae82814a7fb265a969aee26317806bf069ce5))
* refactor to `_useSession` semantics ([#734](https://github.com/luckdev2350/auth-js/issues/734)) ([5d142fa](https://github.com/luckdev2350/auth-js/commit/5d142facc8ea60f1b61a6cf6615d8a1b9ba81d0f))
* Release V2 RC ([9d6d199](https://github.com/luckdev2350/auth-js/commit/9d6d199d78796d6de24d03a1f2e3faf9c64616fc))
* remove `cache: no-store` as it breaks cloudflare ([#886](https://github.com/luckdev2350/auth-js/issues/886)) ([10e9d38](https://github.com/luckdev2350/auth-js/commit/10e9d3871c5a9ce50d15c35c7fd7045cad504670))
* remove all cookie related methods ([6211cf1](https://github.com/luckdev2350/auth-js/commit/6211cf13a93b088eccc894c6c8d0410eb42d2db4))
* remove code param ([#672](https://github.com/luckdev2350/auth-js/issues/672)) ([069e695](https://github.com/luckdev2350/auth-js/commit/069e695ca0b1037c2afa5a013e5c58fa59df540b))
* remove deprecated functions ([1e3ce97](https://github.com/luckdev2350/auth-js/commit/1e3ce971b6eb2aa9f7763f78613263bbeb892378))
* remove experimental from `signInWithSSO`, update docs ([#643](https://github.com/luckdev2350/auth-js/issues/643)) ([759cdc1](https://github.com/luckdev2350/auth-js/commit/759cdc19de9013f69e8ff2a6be9767503e654beb))
* remove session, emit `SIGNED_OUT` when JWT `session_id` is invalid ([#905](https://github.com/luckdev2350/auth-js/issues/905)) ([db41710](https://github.com/luckdev2350/auth-js/commit/db41710b1a35ef559158a936d0a95acc0b1fca96))
* remove stack guards, lock on external calls ([#757](https://github.com/luckdev2350/auth-js/issues/757)) ([617dcfd](https://github.com/luckdev2350/auth-js/commit/617dcfd706bf7e4f3d63ad0419ad573e8d866264))
* rename GoTrueApi to GoTrueAdminApi ([4f6b92a](https://github.com/luckdev2350/auth-js/commit/4f6b92ac5eadcac2798e6f935f56199bb63e8dcb))
* return `messageId` when using otp ([#706](https://github.com/luckdev2350/auth-js/issues/706)) ([b3a6ff4](https://github.com/luckdev2350/auth-js/commit/b3a6ff4f676b8b6209fac9b82d752d1b5923d63c))
* return `weakPassword` information after sign-in ([#824](https://github.com/luckdev2350/auth-js/issues/824)) ([280d908](https://github.com/luckdev2350/auth-js/commit/280d908329daa8221ecc915e3f2df018e3a87e01))
* return pagination data for the `listUsers()` method ([#544](https://github.com/luckdev2350/auth-js/issues/544)) ([d4fe148](https://github.com/luckdev2350/auth-js/commit/d4fe148fcee3d13615b5ef6f1226dd9ba1405b4d))
* revert `_useSession` semantics for unknown issue ([#732](https://github.com/luckdev2350/auth-js/issues/732)) ([8e8eac9](https://github.com/luckdev2350/auth-js/commit/8e8eac9e08a34ac38d08e1b4ac51c3161382d8e3))
* revert use `Deno.unrefTimer` to stop runtime from hanging ([#659](https://github.com/luckdev2350/auth-js/issues/659)) ([2f40f41](https://github.com/luckdev2350/auth-js/commit/2f40f419bfc201af3ef45925f0b47bc56df2c56e))
* setSession triggers SIGNED_IN event ([#581](https://github.com/luckdev2350/auth-js/issues/581)) ([faaaad2](https://github.com/luckdev2350/auth-js/commit/faaaad2fff2e06886450abd9615718102d2a48cf))
* start adding admin mfa bindings ([496f1ec](https://github.com/luckdev2350/auth-js/commit/496f1ec400c43171b99b22e282a70cece68a2836))
* support pagination options for `listUsers()` method ([#537](https://github.com/luckdev2350/auth-js/issues/537)) ([90495c9](https://github.com/luckdev2350/auth-js/commit/90495c908e1f89a98cf657668358a7534def81d8))
* trap errors when `BroadcastChannel` is not supported ([#626](https://github.com/luckdev2350/auth-js/issues/626)) ([1c02c9f](https://github.com/luckdev2350/auth-js/commit/1c02c9f73031f8a18123efa536b69a08c617e4aa))
* update setSession ([e6ee0c6](https://github.com/luckdev2350/auth-js/commit/e6ee0c604390416ae9a317856cad424b52533087))
* update tsdoc ([#687](https://github.com/luckdev2350/auth-js/issues/687)) ([15ef8b7](https://github.com/luckdev2350/auth-js/commit/15ef8b7b4432dc33160e9b39a6a7c1b9cc949556))
* use `&lt;=` for auto refresh token threshold ([#716](https://github.com/luckdev2350/auth-js/issues/716)) ([4c2b3c6](https://github.com/luckdev2350/auth-js/commit/4c2b3c6407f0993ca16de0e201a0d689d581fc92))
* use `Deno.unrefTimer` to stop runtime from hanging ([#632](https://github.com/luckdev2350/auth-js/issues/632)) ([4eddc07](https://github.com/luckdev2350/auth-js/commit/4eddc079326012e20887872e7e9f161f6441d108)), closes [#617](https://github.com/luckdev2350/auth-js/issues/617)
* warn use of `getSession()` when `isServer` on storage ([#846](https://github.com/luckdev2350/auth-js/issues/846)) ([9ea94fe](https://github.com/luckdev2350/auth-js/commit/9ea94fe11f4a6a4b6305aa4fe75c4661074437a7))
* wrap navigator.locks.request with plain promise to help zone.js ([#989](https://github.com/luckdev2350/auth-js/issues/989)) ([2e6e07c](https://github.com/luckdev2350/auth-js/commit/2e6e07c21a561ca13d5e74b69609c2cc93f104f4)), closes [#830](https://github.com/luckdev2350/auth-js/issues/830)


### Bug Fixes

* _getSessionFromUrl() test ([4838a4b](https://github.com/luckdev2350/auth-js/commit/4838a4bc635ebef7f5c076e501e90232d74b61a6))
* `_isPKCEFlow` is not being awaited ([#653](https://github.com/luckdev2350/auth-js/issues/653)) ([35c8e2e](https://github.com/luckdev2350/auth-js/commit/35c8e2e48a304fe5bbb16a8150f8924af11d1cfb))
* `getUser` returns null if there is no session ([#876](https://github.com/luckdev2350/auth-js/issues/876)) ([6adf8ca](https://github.com/luckdev2350/auth-js/commit/6adf8caa4ca803e65f943cc88a2849f5905a044a))
* `isBrowser()` to include check on `window` ([#982](https://github.com/luckdev2350/auth-js/issues/982)) ([645f224](https://github.com/luckdev2350/auth-js/commit/645f22447e68ba13e43e359d1524e95fe025d771))
* add AuthResponse type ([d7881b3](https://github.com/luckdev2350/auth-js/commit/d7881b3d1fcfff305b53267525e13ceb55c1c9b0))
* add ban_duration ([ea900c7](https://github.com/luckdev2350/auth-js/commit/ea900c7f65677865849790e2bbc5808eb222e4d0))
* add custom error classes ([0e0cac4](https://github.com/luckdev2350/auth-js/commit/0e0cac4793b195cc02e9b79f8bcc4f53be0daaa4))
* add email as a verification type ([#642](https://github.com/luckdev2350/auth-js/issues/642)) ([aa78b75](https://github.com/luckdev2350/auth-js/commit/aa78b757a90742be2017147763493f11179b42f3))
* add email change types to generateLink ([fe0663e](https://github.com/luckdev2350/auth-js/commit/fe0663e6eb018f61db39efa346a07f9d1ea20517))
* add email_address_invalid error code ([#994](https://github.com/luckdev2350/auth-js/issues/994)) ([232f133](https://github.com/luckdev2350/auth-js/commit/232f133b1a84b4c667e994f472098aa5cde2088d))
* add emailRedirectTo option to resend method ([#724](https://github.com/luckdev2350/auth-js/issues/724)) ([44af61e](https://github.com/luckdev2350/auth-js/commit/44af61e872fafbbe4a0438f8ad170f0ce5a1acdd))
* add emailRedirectTo option to updateUser ([#610](https://github.com/luckdev2350/auth-js/issues/610)) ([a831a35](https://github.com/luckdev2350/auth-js/commit/a831a356dbef665d8d6e3285c96346494628dd72))
* add figma provider ([#723](https://github.com/luckdev2350/auth-js/issues/723)) ([3fc3b52](https://github.com/luckdev2350/auth-js/commit/3fc3b52549bf5b29414c33f34cb6da9b0303ad2b))
* add forgotten `data` option for sign ins ([37d19aa](https://github.com/luckdev2350/auth-js/commit/37d19aad9117fe88a6ad4d886adb78d3b0697c67))
* add initial enroll and challenge implementations ([e978aac](https://github.com/luckdev2350/auth-js/commit/e978aac4c0775988db60ab1f232e017d0d01240e))
* add loose auto complete to string literals where applicable ([#966](https://github.com/luckdev2350/auth-js/issues/966)) ([fd9248d](https://github.com/luckdev2350/auth-js/commit/fd9248d7aecd0bd00381dff162969d8014a3359a))
* add missing new_phone property ([#609](https://github.com/luckdev2350/auth-js/issues/609)) ([2988031](https://github.com/luckdev2350/auth-js/commit/29880318285037e79ccc2cc153db1b641d077e0e))
* add new error codes ([#979](https://github.com/luckdev2350/auth-js/issues/979)) ([dfb40d2](https://github.com/luckdev2350/auth-js/commit/dfb40d24188f7e8b0d34e51ded15582086250c51))
* add option to pass in data ([d728b6f](https://github.com/luckdev2350/auth-js/commit/d728b6f892784a13fea681f2d6d9c217eec30d6b))
* add password recoery flow support for pkce ([#813](https://github.com/luckdev2350/auth-js/issues/813)) ([e46a324](https://github.com/luckdev2350/auth-js/commit/e46a324d9fbb5e69dd2a5ad0fc816af9e0c535a3))
* add reauthenticate method ([#688](https://github.com/luckdev2350/auth-js/issues/688)) ([0b36795](https://github.com/luckdev2350/auth-js/commit/0b367950c332fba18c2baeadf003043c18a7eb22))
* add soft delete option in deleteUser ([#587](https://github.com/luckdev2350/auth-js/issues/587)) ([1217825](https://github.com/luckdev2350/auth-js/commit/1217825583e26eebe005b83f37bad54deefd4ab1))
* add status property to AuthError ([#580](https://github.com/luckdev2350/auth-js/issues/580)) ([b7b66fe](https://github.com/luckdev2350/auth-js/commit/b7b66fef9e5dc8db755a589ed5a404720832f666))
* add verify token hash ([#722](https://github.com/luckdev2350/auth-js/issues/722)) ([293662c](https://github.com/luckdev2350/auth-js/commit/293662c5f0f79adea0b0ac14234415d1f7887179))
* always wait for `_initialize` before loading the session ([#747](https://github.com/luckdev2350/auth-js/issues/747)) ([67eb616](https://github.com/luckdev2350/auth-js/commit/67eb6169aeb1b1a42d7c7e7cbf6336aef79e55de))
* await _saveSession and _removeSession ([ebf4ce4](https://github.com/luckdev2350/auth-js/commit/ebf4ce48f055af85afbaddf673f1bd23fd596cc2))
* await getSessionFromUrl in _recoverAndRefresh ([4506866](https://github.com/luckdev2350/auth-js/commit/4506866d29ac61c69569b7315a7fc037464f1037))
* better defined localStorage support for debug ([#753](https://github.com/luckdev2350/auth-js/issues/753)) ([6a82b88](https://github.com/luckdev2350/auth-js/commit/6a82b88badff9026d02aba47ce8effec378af1fd))
* bump version ([02876d7](https://github.com/luckdev2350/auth-js/commit/02876d78631e320dc4af9c8af4d631f01789aa02))
* Call `SIGNED_OUT` event where session is removed ([#854](https://github.com/luckdev2350/auth-js/issues/854)) ([436fd9f](https://github.com/luckdev2350/auth-js/commit/436fd9f967ad6d515b8eca179d06032619a1b071))
* change enroll params to snake case ([78044a4](https://github.com/luckdev2350/auth-js/commit/78044a456a6924cdeb9d3daf0d79f9aa23132dd5))
* change setSession to take in an access token ([ed87b76](https://github.com/luckdev2350/auth-js/commit/ed87b7621f51c3a68af6f402577edc5254a14102))
* change setSession to take in an object ([f7e3bc1](https://github.com/luckdev2350/auth-js/commit/f7e3bc175622c975ad0504305c8df59e5787ff78))
* change types to return appropriate signatures ([3c5f2e0](https://github.com/luckdev2350/auth-js/commit/3c5f2e0481f5f834870c1f65b6ea6f90d2f9de82))
* check for access token in header ([#882](https://github.com/luckdev2350/auth-js/issues/882)) ([ae4a53d](https://github.com/luckdev2350/auth-js/commit/ae4a53de7eb41ebde3b4e1abe823e2ffcb53a71d))
* check for Deno ([#658](https://github.com/luckdev2350/auth-js/issues/658)) ([6b9e92a](https://github.com/luckdev2350/auth-js/commit/6b9e92acd6f7e920454ba18136e9bfce69075834))
* clean up signInWithOAuth types ([ef1011f](https://github.com/luckdev2350/auth-js/commit/ef1011f09a9ac3d3fd379e8b27d9a465f5d287df))
* clean up signInWithOAuth types ([9fce93e](https://github.com/luckdev2350/auth-js/commit/9fce93e38575595e5b221088217cd88161733aa7))
* cleanup localStorage session format ([a93adc6](https://github.com/luckdev2350/auth-js/commit/a93adc60d1730d34a6059f178349f55635b1f9a0))
* cleanup type docs ([0fe005c](https://github.com/luckdev2350/auth-js/commit/0fe005cd07b699af8b3ccd2d8cef5d9c6d4651c2))
* correct typo ([828b0b3](https://github.com/luckdev2350/auth-js/commit/828b0b355ef67ac031e02d63476ba70e50450764))
* Correct typo in GoTrueClient warning message ([#938](https://github.com/luckdev2350/auth-js/issues/938)) ([8222ee1](https://github.com/luckdev2350/auth-js/commit/8222ee198a0ab10570e8b4c31ffb2aeafef86392))
* decode base64 to UTF8. ([#528](https://github.com/luckdev2350/auth-js/issues/528)) ([b4ddf4c](https://github.com/luckdev2350/auth-js/commit/b4ddf4c9d3d2321218e48152aba0c81261bd2c56))
* decodeBase64URL compatibility ([#586](https://github.com/luckdev2350/auth-js/issues/586)) ([c9d5d01](https://github.com/luckdev2350/auth-js/commit/c9d5d01ca39f4a3833e081ab79056a736cfe646c))
* default to plain code challenge method if crypto API is undefined ([#663](https://github.com/luckdev2350/auth-js/issues/663)) ([455ff47](https://github.com/luckdev2350/auth-js/commit/455ff470c1a2afeab4f12ff6cfeb7bf22ba84ec2))
* defer `notifyAllSubscribers` in the constructor ([#623](https://github.com/luckdev2350/auth-js/issues/623)) ([6c842b8](https://github.com/luckdev2350/auth-js/commit/6c842b88faaf33bba7e5017f8849361a015f7b0c))
* distinguish between malformed urls and errors ([5db69b0](https://github.com/luckdev2350/auth-js/commit/5db69b04002a51535988f5f502fb26d679eeb5fc))
* don't call removeSession prematurely  ([#915](https://github.com/luckdev2350/auth-js/issues/915)) ([e0dc518](https://github.com/luckdev2350/auth-js/commit/e0dc51849680fa8f1900de786c4a7e77eab8760e))
* don't remove session for identity linking errors ([#987](https://github.com/luckdev2350/auth-js/issues/987)) ([e68ebe6](https://github.com/luckdev2350/auth-js/commit/e68ebe604d15d881b23678d180cccb7115f16f4e))
* don't remove session in resend ([#717](https://github.com/luckdev2350/auth-js/issues/717)) ([48f21e1](https://github.com/luckdev2350/auth-js/commit/48f21e1446c87a9a9835995fb2860932e1160999))
* don't throw error in exchangeCodeForSession ([#946](https://github.com/luckdev2350/auth-js/issues/946)) ([6e161ec](https://github.com/luckdev2350/auth-js/commit/6e161ece3f8cd0d115857e2ed4346533840769f0))
* don't throw errors in constructor ([250923e](https://github.com/luckdev2350/auth-js/commit/250923e2ae0b09592603b2bef9dfc2e96e899496))
* drop experimental MFA tag ([#547](https://github.com/luckdev2350/auth-js/issues/547)) ([5826e9b](https://github.com/luckdev2350/auth-js/commit/5826e9b2d16b0d200d319bfc8a069e1be370d9a8))
* Emit password recovery event from verifyOtp when otp type is recovery ([#829](https://github.com/luckdev2350/auth-js/issues/829)) ([78abe52](https://github.com/luckdev2350/auth-js/commit/78abe522d42513ec566c902fb20b8e9dff2661d6))
* eof newline ([2eea38f](https://github.com/luckdev2350/auth-js/commit/2eea38fc468c809d4b9485586d395806b343cf69))
* export errors ([4c07a72](https://github.com/luckdev2350/auth-js/commit/4c07a72d48fcf27be2475e5521c521a09be3e02a))
* expose role in admin user type ([#790](https://github.com/luckdev2350/auth-js/issues/790)) ([d2ec8ff](https://github.com/luckdev2350/auth-js/commit/d2ec8ff44e3754b51712b6687cb9976b5b2fba02))
* fix broken test ([fc7ac57](https://github.com/luckdev2350/auth-js/commit/fc7ac57e080ba8e9bb25cc9c9bb9697d63a9cfc0))
* fix ts error introduced with prettier changes ([709e3f4](https://github.com/luckdev2350/auth-js/commit/709e3f4691ac368dd421de6df2498fd8eaeea498))
* fixes exponential backoff upon token refresh ([01e39c6](https://github.com/luckdev2350/auth-js/commit/01e39c63fae203d0d8670226050d5c964f93bbde))
* getUser should accept jwt ([7a7075f](https://github.com/luckdev2350/auth-js/commit/7a7075f7028192b8cf903c34980a95901b0da1cb))
* getUser should default to authorization header ([9e8d89f](https://github.com/luckdev2350/auth-js/commit/9e8d89fda28ee07fbdf2e95ff42d0fbd2bfea764))
* handle custom fetch response in error handler ([7371ad6](https://github.com/luckdev2350/auth-js/commit/7371ad674a73884fbc75e337128d5e79d27aefea))
* implement exponential back off on the retries of `_refreshAccessToken` method ([#869](https://github.com/luckdev2350/auth-js/issues/869)) ([f66711d](https://github.com/luckdev2350/auth-js/commit/f66711ddf87ea705a972a860d7ebfb6e0d003c6b))
* improve `mfa.enroll` return types ([#956](https://github.com/luckdev2350/auth-js/issues/956)) ([8a1ec06](https://github.com/luckdev2350/auth-js/commit/8a1ec0602792191bd235d51fd45c0ec2cabdf216))
* limit proxy session warning to once per client instance ([#900](https://github.com/luckdev2350/auth-js/issues/900)) ([4ecfdda](https://github.com/luckdev2350/auth-js/commit/4ecfdda65188b71322753e57622be8eafe97ed6b))
* listFactors should use getUser ([e214bdb](https://github.com/luckdev2350/auth-js/commit/e214bdb6eea6a8dc4ba40bba698df0c1184ad141))
* make types tigher for generateLink ([07adc58](https://github.com/luckdev2350/auth-js/commit/07adc58c37d92151f031b87c0cccc66657f64299))
* make types tighter ([77299d3](https://github.com/luckdev2350/auth-js/commit/77299d37577ee832c1045985b5dffc0b3177aae7))
* mark `captchaToken` option on `verifyOtp` deprecated ([#532](https://github.com/luckdev2350/auth-js/issues/532)) ([c8b73df](https://github.com/luckdev2350/auth-js/commit/c8b73df41a8ecebba95bb970d9357547cee048eb))
* merge rc into mfa ([4f2ada3](https://github.com/luckdev2350/auth-js/commit/4f2ada37a285bedef24acecf4a1afc3372975f91))
* mfa admin list factors ([#562](https://github.com/luckdev2350/auth-js/issues/562)) ([2b65646](https://github.com/luckdev2350/auth-js/commit/2b65646854bd2ff4911f981075c51a856619a2a5))
* mfa challenge and verify ([bf53819](https://github.com/luckdev2350/auth-js/commit/bf53819136b2c08b366d3c4efbe6fc62a627ca9b))
* mfa verify should update current session ([9ed8fcc](https://github.com/luckdev2350/auth-js/commit/9ed8fcc775f174b1e5ac9fc266f158c4d9dfc79f))
* move  channel parameter from sign in to sign up ([#647](https://github.com/luckdev2350/auth-js/issues/647)) ([e83caba](https://github.com/luckdev2350/auth-js/commit/e83cabad9f66ad7c380198d04599b1b22adc380b))
* move docker compose to v2 ([#940](https://github.com/luckdev2350/auth-js/issues/940)) ([38eef89](https://github.com/luckdev2350/auth-js/commit/38eef89ff61b49eb65ee26b7d2201148d1fc3b77))
* move isBrowser localStorage check ([dffd2b9](https://github.com/luckdev2350/auth-js/commit/dffd2b96c5ec5c9172b6f877b1ce49afc086ed29))
* move MFA sub types to internal file ([#964](https://github.com/luckdev2350/auth-js/issues/964)) ([4b7455c](https://github.com/luckdev2350/auth-js/commit/4b7455c2631ca4e00f01275c7342eb37756ede23))
* move options into verifyOtp params ([262f7e9](https://github.com/luckdev2350/auth-js/commit/262f7e94b3ec81d0f4c50fc7a364b8114d276080))
* move resetPasswordForEmail and refreshAccessToken to GoTrueClient ([8f1d19e](https://github.com/luckdev2350/auth-js/commit/8f1d19e2a396eef6a046f17da3576edc3257d6fe))
* onAuthStateChange returns data object ([0210ed2](https://github.com/luckdev2350/auth-js/commit/0210ed276ff78a7b368d8774d32983b387c1abe6))
* only remove session when there is an invalid one ([ef412f1](https://github.com/luckdev2350/auth-js/commit/ef412f18478e6b73c83bbb60ebebe6912b317718))
* patch release workflow ([#922](https://github.com/luckdev2350/auth-js/issues/922)) ([f84fb50](https://github.com/luckdev2350/auth-js/commit/f84fb50a4357af49acac6ca151057d2af74d63c9))
* pkce does not generate truly random values in a browser ([#636](https://github.com/luckdev2350/auth-js/issues/636)) ([095a756](https://github.com/luckdev2350/auth-js/commit/095a756d73fae9efb685160c81998a2f5bc220aa))
* properly handle non AuthError's ([ff228a7](https://github.com/luckdev2350/auth-js/commit/ff228a755cd81d52ced1865274d29bd01b7ee506))
* refactor all pkce code into a single method ([#860](https://github.com/luckdev2350/auth-js/issues/860)) ([860bffc](https://github.com/luckdev2350/auth-js/commit/860bffc8f75292e71630fb7241e11a754200dab8))
* refactor update method ([f794b1b](https://github.com/luckdev2350/auth-js/commit/f794b1b11bb3996642e0cf1774ae454a70447865))
* refactor user methods ([49aef46](https://github.com/luckdev2350/auth-js/commit/49aef4631c5536fa4e0d7e2e5f3c5f1367c73fa4))
* refreshSession should take in an optional refreshToken ([4d20e57](https://github.com/luckdev2350/auth-js/commit/4d20e570465c3f7bd19c63b644b510eb73b0f4a7))
* refreshSession() test ([62996c2](https://github.com/luckdev2350/auth-js/commit/62996c2c4ab9b12c1d72ac42f4d3911b3cedc421))
* remove _recoverSession ([6ee6f10](https://github.com/luckdev2350/auth-js/commit/6ee6f10334d2008409a5eae83693e07c3c6ceb6f))
* remove `internal-types.ts` ([#1014](https://github.com/luckdev2350/auth-js/issues/1014)) ([28ead89](https://github.com/luckdev2350/auth-js/commit/28ead89af47bcdaccc6cc2f2c7f013bed8cf3d50))
* remove access token and jwt code ([b5d807d](https://github.com/luckdev2350/auth-js/commit/b5d807d27d7125b6dcf76438dc3ade8de034ff06))
* remove async from `generatePKCEVerifier` and fix parameter of `_handleProviderSignIn` ([#638](https://github.com/luckdev2350/auth-js/issues/638)) ([ea007ca](https://github.com/luckdev2350/auth-js/commit/ea007caa1b64feec32502d41a9ad8b4f8fd51af1))
* remove comments about calling `getUser()` in listFactors() ([#570](https://github.com/luckdev2350/auth-js/issues/570)) ([16d3deb](https://github.com/luckdev2350/auth-js/commit/16d3deb822097e8640a3a15b94a5690b3beaf11b))
* remove crypto-js ([#641](https://github.com/luckdev2350/auth-js/issues/641)) ([09b60e5](https://github.com/luckdev2350/auth-js/commit/09b60e50e43398368c52ff4b0e24ec860c1a119c))
* remove data property from AdminUserAttributes ([#612](https://github.com/luckdev2350/auth-js/issues/612)) ([e91b379](https://github.com/luckdev2350/auth-js/commit/e91b379a0f44c7d3b7ad628c362b8cd4b46cf638))
* remove data type ([#848](https://github.com/luckdev2350/auth-js/issues/848)) ([15c7c82](https://github.com/luckdev2350/auth-js/commit/15c7c8258b2d42d3378be4f7738c728a07523579))
* remove duplicated methods in GoTrueApi ([f6d9c41](https://github.com/luckdev2350/auth-js/commit/f6d9c41c97d5dae2f28789680931b13e7696b1fc))
* remove multitab stuff ([0a9814b](https://github.com/luckdev2350/auth-js/commit/0a9814b5df7de4d928d8e92bd497a38f236c5b65))
* remove oauth flow type ([#655](https://github.com/luckdev2350/auth-js/issues/655)) ([f0089fa](https://github.com/luckdev2350/auth-js/commit/f0089fa46289f18f8ac013c48f9ff013b2e0e1df))
* remove phone mfa deletion, match on error codes ([#963](https://github.com/luckdev2350/auth-js/issues/963)) ([ef3911c](https://github.com/luckdev2350/auth-js/commit/ef3911cd1a082a6825ce25fe326081e096bd55f5))
* remove unnecessary notify events ([31c9041](https://github.com/luckdev2350/auth-js/commit/31c9041f83f3d13c295e73b64cc9e31050cbe5fb))
* remove xform methods ([5c43ca5](https://github.com/luckdev2350/auth-js/commit/5c43ca5ffda8b9cccc493a47a4d3a6194a057ad2))
* rename localstorage to storage ([41e66e6](https://github.com/luckdev2350/auth-js/commit/41e66e673985b42df939ce7aec223c1c852c2e28))
* resolve & reset deferred upon refresh error ([90ed495](https://github.com/luckdev2350/auth-js/commit/90ed4953e9c77877e11da2a2030de13e16ffecf4))
* return error early for redirects ([#992](https://github.com/luckdev2350/auth-js/issues/992)) ([9f32d30](https://github.com/luckdev2350/auth-js/commit/9f32d30e17954c5d4320b374a108617cda5ab357))
* return error if missing session or missing custom auth header ([#891](https://github.com/luckdev2350/auth-js/issues/891)) ([8d16578](https://github.com/luckdev2350/auth-js/commit/8d165787ec46929cba68d18c35161463240f61e3))
* return provider refresh token ([7640bd7](https://github.com/luckdev2350/auth-js/commit/7640bd7ec9c52aaa2fc4365c544f54513293df2e))
* return redirect errors early  ([#1003](https://github.com/luckdev2350/auth-js/issues/1003)) ([9751b80](https://github.com/luckdev2350/auth-js/commit/9751b8029b4235a63dcb525e7ce7cc942c85daf5))
* return warning if `persistSession` is true with no storage option ([#697](https://github.com/luckdev2350/auth-js/issues/697)) ([4664066](https://github.com/luckdev2350/auth-js/commit/46640661a9f9771bef6ac6354bea0f576509a6e0))
* Revert "fix: `getUser` returns null if there is no session ([#876](https://github.com/luckdev2350/auth-js/issues/876))" ([#889](https://github.com/luckdev2350/auth-js/issues/889)) ([6755fef](https://github.com/luckdev2350/auth-js/commit/6755fef2aefd1bc84a26182f848c0912492cb106))
* revert "fix: respect `EXPIRY_MARGIN` on `getSession`" ([#533](https://github.com/luckdev2350/auth-js/issues/533)) ([e9e0a01](https://github.com/luckdev2350/auth-js/commit/e9e0a01ad763d159cf425ff2b093db6a921cd4bb))
* revert [#992](https://github.com/luckdev2350/auth-js/issues/992) and [#993](https://github.com/luckdev2350/auth-js/issues/993) ([#999](https://github.com/luckdev2350/auth-js/issues/999)) ([12b2848](https://github.com/luckdev2350/auth-js/commit/12b2848237854f3d70b9989920ad50e2c4186fff))
* revert check for access token in header ([#885](https://github.com/luckdev2350/auth-js/issues/885)) ([03d8ba7](https://github.com/luckdev2350/auth-js/commit/03d8ba7ca5c485979788d6f121199e4370622491))
* revert pop implicit flow URL from back stack ([#596](https://github.com/luckdev2350/auth-js/issues/596)) ([8eb91a6](https://github.com/luckdev2350/auth-js/commit/8eb91a66c27fffad90fde72d837fa53ef83d1432))
* revert using @supabase/node-fetch ([#765](https://github.com/luckdev2350/auth-js/issues/765)) ([22923e7](https://github.com/luckdev2350/auth-js/commit/22923e7ea4780287e9a6b4c596889c51a00b9039))
* send `application/json` in Content-Type header  ([#429](https://github.com/luckdev2350/auth-js/issues/429)) ([0fc980c](https://github.com/luckdev2350/auth-js/commit/0fc980cfbdf48be3a919a45d164d4bdf2bbee64f))
* send headers on all requests ([5dfdd94](https://github.com/luckdev2350/auth-js/commit/5dfdd941bde489845810076b14ded4e9b6ad5d9d))
* setSession is in broken state after v2.4.0 ([#548](https://github.com/luckdev2350/auth-js/issues/548)) ([0fcc8f5](https://github.com/luckdev2350/auth-js/commit/0fcc8f576d255b92e4e8bdc57c450e8b3390b700))
* signInWithPassword should send sign-in event ([92e4f0e](https://github.com/luckdev2350/auth-js/commit/92e4f0e3ca18590c150b841d2103df59b464624d))
* signOut should ignore 403s ([#894](https://github.com/luckdev2350/auth-js/issues/894)) ([eeb77ce](https://github.com/luckdev2350/auth-js/commit/eeb77ce2a1ddee94c38f17533c9b748bf2950f67))
* signOut should remove any unused code verifier ([#664](https://github.com/luckdev2350/auth-js/issues/664)) ([a922241](https://github.com/luckdev2350/auth-js/commit/a922241dbe2299e8ecfe3712b84111f9d308607c))
* signout should remove session if user doesn't exist ([#541](https://github.com/luckdev2350/auth-js/issues/541)) ([ed8fe4f](https://github.com/luckdev2350/auth-js/commit/ed8fe4f471b8773a5f49d8528785f5aafdd81093))
* spelling ([56b765e](https://github.com/luckdev2350/auth-js/commit/56b765ecd20bff80cf346b0db60710e91d9c6a7f))
* suppress getSession warning whenever _saveSession is called ([#895](https://github.com/luckdev2350/auth-js/issues/895)) ([59ec9af](https://github.com/luckdev2350/auth-js/commit/59ec9affa01c780fb18f668291fa7167a65c391d))
* throw AuthRetryableFetchError on network errors only ([7e7f32f](https://github.com/luckdev2350/auth-js/commit/7e7f32fb505ed667c5da1cc0ca63e0d74a4c048a))
* tidy up tab issue in unrelated code ([9031ee9](https://github.com/luckdev2350/auth-js/commit/9031ee9a3040e83256a4545a7858a4469e3bf5c1))
* Type error on code exchange when no item in storage ([#825](https://github.com/luckdev2350/auth-js/issues/825)) ([6d6ec13](https://github.com/luckdev2350/auth-js/commit/6d6ec13fc518fc85adf9ededd97e3d37140fe584))
* type errors in verifyOtp ([#918](https://github.com/luckdev2350/auth-js/issues/918)) ([dcd0b9b](https://github.com/luckdev2350/auth-js/commit/dcd0b9b682412a2f1d2deaab26eb8094e50b67fd))
* typedocs docs ([d4a49ee](https://github.com/luckdev2350/auth-js/commit/d4a49ee5317a0b8d6ad960a00aa4cc3a0c730894))
* typo ([#786](https://github.com/luckdev2350/auth-js/issues/786)) ([45b6e3e](https://github.com/luckdev2350/auth-js/commit/45b6e3e656f842c60ebe2709f59bad4eb6f5811e))
* typo in auth cookie error ([489af4d](https://github.com/luckdev2350/auth-js/commit/489af4de5f08a1951aa080134f1aebbf05f43eae))
* typo in warning message ([#975](https://github.com/luckdev2350/auth-js/issues/975)) ([4f21f93](https://github.com/luckdev2350/auth-js/commit/4f21f9324b2c3d55630b8d0a6759a264b0472dd8))
* update corresponding type for TOTP ([65d9505](https://github.com/luckdev2350/auth-js/commit/65d95056b83786dcef1e878233c54c917a3cb917))
* update default value from totp -&gt; TOTP ([c36fa1c](https://github.com/luckdev2350/auth-js/commit/c36fa1c71023cf937c6b1565c6291b1ee9caa41d))
* update docs to add scrypt ([#1012](https://github.com/luckdev2350/auth-js/issues/1012)) ([1225239](https://github.com/luckdev2350/auth-js/commit/1225239e239bde1b25037a88867d4c484caf8301))
* update getAAL and getAMR methods ([792ea21](https://github.com/luckdev2350/auth-js/commit/792ea21ea825b083a4b53d2177912df8456ebdd3))
* update getAuthenticatorAssuranceLevel ([4559cf3](https://github.com/luckdev2350/auth-js/commit/4559cf3a9cd1bc3aee52c2d76891c5326f0c64c7))
* update mfa methods ([#551](https://github.com/luckdev2350/auth-js/issues/551)) ([958d948](https://github.com/luckdev2350/auth-js/commit/958d94811fba9ef2ff23e278c85974cb909802da))
* update resend types ([#691](https://github.com/luckdev2350/auth-js/issues/691)) ([aa47a89](https://github.com/luckdev2350/auth-js/commit/aa47a89561f6202024c8aeed7cb5fb1e49bad8c1))
* update session warning ([#879](https://github.com/luckdev2350/auth-js/issues/879)) ([3661130](https://github.com/luckdev2350/auth-js/commit/36611300fa6d1378a7633c62d2f816d3803f2774))
* update soft-deletion docs ([#973](https://github.com/luckdev2350/auth-js/issues/973)) ([cb052a9](https://github.com/luckdev2350/auth-js/commit/cb052a9b0846048feef18080d830cc36a9ed7282))
* update to node 18 ([#582](https://github.com/luckdev2350/auth-js/issues/582)) ([1947a4a](https://github.com/luckdev2350/auth-js/commit/1947a4a2f6d0bc419d21c834e9c8205be3d7605c))
* update tsdocs ([#559](https://github.com/luckdev2350/auth-js/issues/559)) ([a2920dd](https://github.com/luckdev2350/auth-js/commit/a2920dd5ea0af9cd47ee0d3a3d57dc9707f7e768))
* update types  ([#930](https://github.com/luckdev2350/auth-js/issues/930)) ([dbc5962](https://github.com/luckdev2350/auth-js/commit/dbc5962d609cc0470b5b03160f4cd8b9e7d03ce3))
* update types for generateLink ([99f1bec](https://github.com/luckdev2350/auth-js/commit/99f1bec559b0da7ca01d3721cfd7136fe4ff9f82))
* upgrade to node 20 ([#839](https://github.com/luckdev2350/auth-js/issues/839)) ([3c74318](https://github.com/luckdev2350/auth-js/commit/3c7431835af9cf4b2968bd42f474f84c73c9fc65))
* use @supabase/node-fetch ([#763](https://github.com/luckdev2350/auth-js/issues/763)) ([bdfd212](https://github.com/luckdev2350/auth-js/commit/bdfd212c0b5035f4c44004cc7e00c4fb8823bdf0))
* use @supabase/node-fetch ([#776](https://github.com/luckdev2350/auth-js/issues/776)) ([e0b9c9f](https://github.com/luckdev2350/auth-js/commit/e0b9c9f718de99ecbbfca224a30ba8ea5bf3cd01))
* use `captcha_token` in `verifyOtp` ([#525](https://github.com/luckdev2350/auth-js/issues/525)) ([321a95e](https://github.com/luckdev2350/auth-js/commit/321a95e23e3a52029d4ef8b571a5f0971239bffb))
* use `location.assign()` instead of `location.href` ([#573](https://github.com/luckdev2350/auth-js/issues/573)) ([26344e4](https://github.com/luckdev2350/auth-js/commit/26344e4e6d6fbd95cec8f09d85a2e3edba87410a)), closes [#155](https://github.com/luckdev2350/auth-js/issues/155)
* use `unref` on `setInterval` to stop tests from hanging ([#599](https://github.com/luckdev2350/auth-js/issues/599)) ([1d8df28](https://github.com/luckdev2350/auth-js/commit/1d8df28364dc5402c374668e619a42696094f096))
* use current session in _startAutoRefreshToken callback ([83f48ab](https://github.com/luckdev2350/auth-js/commit/83f48ab86182a11ff43c9ae7743a90e4ab0a7e18))
* use snake_case in req body keys ([fcc4306](https://github.com/luckdev2350/auth-js/commit/fcc43064cfbc5209aad5bbd4b75f21ff9b023f8f))
* validate error callback urls ([c065fd4](https://github.com/luckdev2350/auth-js/commit/c065fd400cd1009be76439963fdefac032c213e3))
* verifyOtp should not removeSession for phone_change & email_change ([#698](https://github.com/luckdev2350/auth-js/issues/698)) ([83bc5b6](https://github.com/luckdev2350/auth-js/commit/83bc5b62ef9c951c1eb445c037a1d10abdf9f401))
* verifyOTP should send session ([81b52db](https://github.com/luckdev2350/auth-js/commit/81b52db0a621bcc10af4cb1f2ea768782c701ee1))
* wait for _getSessionFromUrl ([4018cae](https://github.com/luckdev2350/auth-js/commit/4018cae132e7eda3dc10a35481c2f0917a186463))
* weak password error runtime type checks ([#819](https://github.com/luckdev2350/auth-js/issues/819)) ([016ee66](https://github.com/luckdev2350/auth-js/commit/016ee66b3183c3bb00c9e954dbf4226319756f76))

## [2.68.0](https://github.com/supabase/auth-js/compare/v2.67.3...v2.68.0) (2025-01-21)


### Features

* consider session expired with margin on getSession() without auto refresh ([#1027](https://github.com/supabase/auth-js/issues/1027)) ([80f88e4](https://github.com/supabase/auth-js/commit/80f88e4bd2809db765a8d103954e827d8473b7db))


### Bug Fixes

* remove `internal-types.ts` ([#1014](https://github.com/supabase/auth-js/issues/1014)) ([28ead89](https://github.com/supabase/auth-js/commit/28ead89af47bcdaccc6cc2f2c7f013bed8cf3d50))
* update docs to add scrypt ([#1012](https://github.com/supabase/auth-js/issues/1012)) ([1225239](https://github.com/supabase/auth-js/commit/1225239e239bde1b25037a88867d4c484caf8301))

## [2.67.3](https://github.com/supabase/auth-js/compare/v2.67.2...v2.67.3) (2024-12-17)


### Bug Fixes

* return redirect errors early  ([#1003](https://github.com/supabase/auth-js/issues/1003)) ([9751b80](https://github.com/supabase/auth-js/commit/9751b8029b4235a63dcb525e7ce7cc942c85daf5))

## [2.67.2](https://github.com/supabase/auth-js/compare/v2.67.1...v2.67.2) (2024-12-16)


### Bug Fixes

* `isBrowser()` to include check on `window` ([#982](https://github.com/supabase/auth-js/issues/982)) ([645f224](https://github.com/supabase/auth-js/commit/645f22447e68ba13e43e359d1524e95fe025d771))

## [2.67.1](https://github.com/supabase/auth-js/compare/v2.67.0...v2.67.1) (2024-12-13)


### Bug Fixes

* revert [#992](https://github.com/supabase/auth-js/issues/992) and [#993](https://github.com/supabase/auth-js/issues/993) ([#999](https://github.com/supabase/auth-js/issues/999)) ([12b2848](https://github.com/supabase/auth-js/commit/12b2848237854f3d70b9989920ad50e2c4186fff))

## [2.67.0](https://github.com/supabase/auth-js/compare/v2.66.1...v2.67.0) (2024-12-12)


### Features

* wrap navigator.locks.request with plain promise to help zone.js ([#989](https://github.com/supabase/auth-js/issues/989)) ([2e6e07c](https://github.com/supabase/auth-js/commit/2e6e07c21a561ca13d5e74b69609c2cc93f104f4)), closes [#830](https://github.com/supabase/auth-js/issues/830)


### Bug Fixes

* add email_address_invalid error code ([#994](https://github.com/supabase/auth-js/issues/994)) ([232f133](https://github.com/supabase/auth-js/commit/232f133b1a84b4c667e994f472098aa5cde2088d))
* return error early for redirects ([#992](https://github.com/supabase/auth-js/issues/992)) ([9f32d30](https://github.com/supabase/auth-js/commit/9f32d30e17954c5d4320b374a108617cda5ab357))

## [2.66.1](https://github.com/supabase/auth-js/compare/v2.66.0...v2.66.1) (2024-12-04)


### Bug Fixes

* add loose auto complete to string literals where applicable ([#966](https://github.com/supabase/auth-js/issues/966)) ([fd9248d](https://github.com/supabase/auth-js/commit/fd9248d7aecd0bd00381dff162969d8014a3359a))
* add new error codes ([#979](https://github.com/supabase/auth-js/issues/979)) ([dfb40d2](https://github.com/supabase/auth-js/commit/dfb40d24188f7e8b0d34e51ded15582086250c51))
* don't remove session for identity linking errors ([#987](https://github.com/supabase/auth-js/issues/987)) ([e68ebe6](https://github.com/supabase/auth-js/commit/e68ebe604d15d881b23678d180cccb7115f16f4e))

## [2.66.0](https://github.com/supabase/auth-js/compare/v2.65.1...v2.66.0) (2024-11-01)


### Features

* add process lock for optional use in non-browser environments (React Native) ([#977](https://github.com/supabase/auth-js/issues/977)) ([8af88b6](https://github.com/supabase/auth-js/commit/8af88b6f4e41872b73e84c40f71793dab6c62126))


### Bug Fixes

* typo in warning message ([#975](https://github.com/supabase/auth-js/issues/975)) ([4f21f93](https://github.com/supabase/auth-js/commit/4f21f9324b2c3d55630b8d0a6759a264b0472dd8))
* update soft-deletion docs ([#973](https://github.com/supabase/auth-js/issues/973)) ([cb052a9](https://github.com/supabase/auth-js/commit/cb052a9b0846048feef18080d830cc36a9ed7282))

## [2.65.1](https://github.com/supabase/auth-js/compare/v2.65.0...v2.65.1) (2024-10-14)


### Bug Fixes

* Call `SIGNED_OUT` event where session is removed ([#854](https://github.com/supabase/auth-js/issues/854)) ([436fd9f](https://github.com/supabase/auth-js/commit/436fd9f967ad6d515b8eca179d06032619a1b071))
* improve `mfa.enroll` return types ([#956](https://github.com/supabase/auth-js/issues/956)) ([8a1ec06](https://github.com/supabase/auth-js/commit/8a1ec0602792191bd235d51fd45c0ec2cabdf216))
* move MFA sub types to internal file ([#964](https://github.com/supabase/auth-js/issues/964)) ([4b7455c](https://github.com/supabase/auth-js/commit/4b7455c2631ca4e00f01275c7342eb37756ede23))
* remove phone mfa deletion, match on error codes ([#963](https://github.com/supabase/auth-js/issues/963)) ([ef3911c](https://github.com/supabase/auth-js/commit/ef3911cd1a082a6825ce25fe326081e096bd55f5))

## [2.65.0](https://github.com/supabase/auth-js/compare/v2.64.4...v2.65.0) (2024-08-27)


### Features

* add bindings for Multi-Factor Authentication (Phone) ([#932](https://github.com/supabase/auth-js/issues/932)) ([b957c30](https://github.com/supabase/auth-js/commit/b957c30782065e4cc421a526c62c101d35c443d4))
* add kakao to sign in with ID token ([#845](https://github.com/supabase/auth-js/issues/845)) ([e2337ba](https://github.com/supabase/auth-js/commit/e2337bad535598d9f751505de52a18c59f1505c3))
* remove session, emit `SIGNED_OUT` when JWT `session_id` is invalid ([#905](https://github.com/supabase/auth-js/issues/905)) ([db41710](https://github.com/supabase/auth-js/commit/db41710b1a35ef559158a936d0a95acc0b1fca96))


### Bug Fixes

* Correct typo in GoTrueClient warning message ([#938](https://github.com/supabase/auth-js/issues/938)) ([8222ee1](https://github.com/supabase/auth-js/commit/8222ee198a0ab10570e8b4c31ffb2aeafef86392))
* don't throw error in exchangeCodeForSession ([#946](https://github.com/supabase/auth-js/issues/946)) ([6e161ec](https://github.com/supabase/auth-js/commit/6e161ece3f8cd0d115857e2ed4346533840769f0))
* move docker compose to v2 ([#940](https://github.com/supabase/auth-js/issues/940)) ([38eef89](https://github.com/supabase/auth-js/commit/38eef89ff61b49eb65ee26b7d2201148d1fc3b77))

## [2.64.4](https://github.com/supabase/auth-js/compare/v2.64.3...v2.64.4) (2024-07-12)


### Bug Fixes

* update types  ([#930](https://github.com/supabase/auth-js/issues/930)) ([dbc5962](https://github.com/supabase/auth-js/commit/dbc5962d609cc0470b5b03160f4cd8b9e7d03ce3))

## [2.64.3](https://github.com/supabase/auth-js/compare/v2.64.2...v2.64.3) (2024-06-17)


### Bug Fixes

* don't call removeSession prematurely  ([#915](https://github.com/supabase/auth-js/issues/915)) ([e0dc518](https://github.com/supabase/auth-js/commit/e0dc51849680fa8f1900de786c4a7e77eab8760e))
* limit proxy session warning to once per client instance ([#900](https://github.com/supabase/auth-js/issues/900)) ([4ecfdda](https://github.com/supabase/auth-js/commit/4ecfdda65188b71322753e57622be8eafe97ed6b))
* patch release workflow ([#922](https://github.com/supabase/auth-js/issues/922)) ([f84fb50](https://github.com/supabase/auth-js/commit/f84fb50a4357af49acac6ca151057d2af74d63c9))
* type errors in verifyOtp ([#918](https://github.com/supabase/auth-js/issues/918)) ([dcd0b9b](https://github.com/supabase/auth-js/commit/dcd0b9b682412a2f1d2deaab26eb8094e50b67fd))

## [2.64.2](https://github.com/supabase/auth-js/compare/v2.64.1...v2.64.2) (2024-05-03)


### Bug Fixes

* signOut should ignore 403s ([#894](https://github.com/supabase/auth-js/issues/894)) ([eeb77ce](https://github.com/supabase/auth-js/commit/eeb77ce2a1ddee94c38f17533c9b748bf2950f67))
* suppress getSession warning whenever _saveSession is called ([#895](https://github.com/supabase/auth-js/issues/895)) ([59ec9af](https://github.com/supabase/auth-js/commit/59ec9affa01c780fb18f668291fa7167a65c391d))

## [2.64.1](https://github.com/supabase/auth-js/compare/v2.64.0...v2.64.1) (2024-04-25)


### Bug Fixes

* return error if missing session or missing custom auth header ([#891](https://github.com/supabase/auth-js/issues/891)) ([8d16578](https://github.com/supabase/auth-js/commit/8d165787ec46929cba68d18c35161463240f61e3))

## [2.64.0](https://github.com/supabase/auth-js/compare/v2.63.2...v2.64.0) (2024-04-25)


### Features

* remove `cache: no-store` as it breaks cloudflare ([#886](https://github.com/supabase/auth-js/issues/886)) ([10e9d38](https://github.com/supabase/auth-js/commit/10e9d3871c5a9ce50d15c35c7fd7045cad504670))


### Bug Fixes

* Revert "fix: `getUser` returns null if there is no session ([#876](https://github.com/supabase/auth-js/issues/876))" ([#889](https://github.com/supabase/auth-js/issues/889)) ([6755fef](https://github.com/supabase/auth-js/commit/6755fef2aefd1bc84a26182f848c0912492cb106))
* revert check for access token in header ([#885](https://github.com/supabase/auth-js/issues/885)) ([03d8ba7](https://github.com/supabase/auth-js/commit/03d8ba7ca5c485979788d6f121199e4370622491))

## [2.63.2](https://github.com/supabase/auth-js/compare/v2.63.1...v2.63.2) (2024-04-20)


### Bug Fixes

* check for access token in header ([#882](https://github.com/supabase/auth-js/issues/882)) ([ae4a53d](https://github.com/supabase/auth-js/commit/ae4a53de7eb41ebde3b4e1abe823e2ffcb53a71d))

## [2.63.1](https://github.com/supabase/auth-js/compare/v2.63.0...v2.63.1) (2024-04-18)


### Bug Fixes

* `getUser` returns null if there is no session ([#876](https://github.com/supabase/auth-js/issues/876)) ([6adf8ca](https://github.com/supabase/auth-js/commit/6adf8caa4ca803e65f943cc88a2849f5905a044a))
* implement exponential back off on the retries of `_refreshAccessToken` method ([#869](https://github.com/supabase/auth-js/issues/869)) ([f66711d](https://github.com/supabase/auth-js/commit/f66711ddf87ea705a972a860d7ebfb6e0d003c6b))
* update session warning ([#879](https://github.com/supabase/auth-js/issues/879)) ([3661130](https://github.com/supabase/auth-js/commit/36611300fa6d1378a7633c62d2f816d3803f2774))

## [2.63.0](https://github.com/supabase/gotrue-js/compare/v2.62.2...v2.63.0) (2024-03-26)


### Features

* add method for anonymous sign-in ([#858](https://github.com/supabase/gotrue-js/issues/858)) ([e8a1fc9](https://github.com/supabase/gotrue-js/commit/e8a1fc9a40947b949080107138eade09f06f5868))
* add support for error codes ([#855](https://github.com/supabase/gotrue-js/issues/855)) ([99821f4](https://github.com/supabase/gotrue-js/commit/99821f4a1f6fdb3a222cd0f660210016e6cc823e))
* explicit `cache: no-store` in fetch ([#847](https://github.com/supabase/gotrue-js/issues/847)) ([034bee0](https://github.com/supabase/gotrue-js/commit/034bee09c3f0a4613d9a3e7bd3bc5f70682f5a66))
* warn use of `getSession()` when `isServer` on storage ([#846](https://github.com/supabase/gotrue-js/issues/846)) ([9ea94fe](https://github.com/supabase/gotrue-js/commit/9ea94fe11f4a6a4b6305aa4fe75c4661074437a7))


### Bug Fixes

* refactor all pkce code into a single method ([#860](https://github.com/supabase/gotrue-js/issues/860)) ([860bffc](https://github.com/supabase/gotrue-js/commit/860bffc8f75292e71630fb7241e11a754200dab8))
* remove data type ([#848](https://github.com/supabase/gotrue-js/issues/848)) ([15c7c82](https://github.com/supabase/gotrue-js/commit/15c7c8258b2d42d3378be4f7738c728a07523579))
