# Chrome Autofill + Auto-Submit - TODO

## Approved Plan Steps
1. [x] Update app/page.js: Add autocomplete attrs, phone type='tel', autofill detection (useEffect polling + events), auto-validate/submit on fill
2. [ ] Restart dev server: `powershell -ExecutionPolicy Bypass -Command \"npm run dev\"`
3. [ ] Verify in Chrome: Autofill form (name/email/phone/address), confirm auto-submit ~1s after fill
4. [ ] Complete: Feature working, update TODO.

**Updated:** app/page.js with full Chrome autofill support (polling detects autofill changes, auto-submits if valid after 1s). Fixed hobby save in submit. Test now!
