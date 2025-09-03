# TODO: Fix Vercel Deployment Issues

## Steps to Complete:
- [x] Fix root vercel.json for correct frontend build and routing
- [x] Remove frontend/vercel.json to avoid conflicts
- [x] Convert backend to serverless API routes
- [x] Create models and utils for serverless functions
- [ ] Commit and push changes to git repo
- [ ] Set environment variables in Vercel dashboard (MONGO_URI, JWT_SECRET)
- [ ] Test deployment on Vercel

## Notes:
- Backend converted to serverless functions under /api folder
- Frontend API calls already use relative paths (/api/...)
- Ensure MONGO_URI and JWT_SECRET are set in Vercel environment variables
- Git repo is at https://github.com/vaibhavsingh1015/Task-Manager-frontend.git
- User should run: git add ., git commit -m "Fix Vercel deployment", git push in the manager folder
