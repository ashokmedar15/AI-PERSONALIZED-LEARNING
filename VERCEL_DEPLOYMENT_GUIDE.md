# 🚀 Vercel Deployment Guide - AI-Powered Educational Platform

## 📋 Prerequisites

- ✅ **GitHub Repository**: [https://github.com/ashokmedar15/AI-PERSONALIZED-LEARNING](https://github.com/ashokmedar15/AI-PERSONALIZED-LEARNING)
- ✅ **Groq AI API Key**: Get from [https://console.groq.com/](https://console.groq.com/)
- ✅ **Vercel Account**: Free tier available

## 🎯 Step-by-Step Vercel Deployment

### Step 1: Create Vercel Account

1. **Visit Vercel**: Go to [vercel.com](https://vercel.com)
2. **Sign Up**: Click "Sign Up" or "Continue with GitHub"
3. **Authorize**: Allow Vercel to access your GitHub account
4. **Complete Setup**: Follow the onboarding process

### Step 2: Import Your Project

1. **Dashboard**: After login, you'll see the Vercel dashboard
2. **New Project**: Click "New Project" button
3. **Import Repository**: 
   - You should see `AI-PERSONALIZED-LEARNING` in the list
   - If not, click "Import Git Repository" and search for it
4. **Select Repository**: Click on `AI-PERSONALIZED-LEARNING`

### Step 3: Configure Project Settings

1. **Project Name**: 
   - Keep default: `ai-personalized-learning`
   - Or customize: `your-ai-education-platform`

2. **Framework Preset**: 
   - Vercel should auto-detect: **Next.js**
   - If not, select "Next.js" manually

3. **Root Directory**: 
   - Leave as default: `./` (root of repository)

4. **Build Command**: 
   - Leave as default: `npm run build`

5. **Output Directory**: 
   - Leave as default: `.next`

6. **Install Command**: 
   - Leave as default: `npm install`

### Step 4: Environment Variables Setup

**⚠️ CRITICAL STEP - Don't skip this!**

1. **Expand Environment Variables**: Click "Environment Variables" section
2. **Add Variable**:
   - **Name**: `GROQ_API_KEY`
   - **Value**: Your Groq API key from [console.groq.com](https://console.groq.com/)
   - **Environment**: Select all three (Production, Preview, Development)
3. **Save**: Click "Add" button

**How to get Groq API Key:**
1. Go to [https://console.groq.com/](https://console.groq.com/)
2. Sign up/Login
3. Navigate to "API Keys" section
4. Create new API key
5. Copy the key (starts with `gsk_...`)

### Step 5: Deploy

1. **Review Settings**: Double-check all configurations
2. **Deploy**: Click "Deploy" button
3. **Wait**: Vercel will build and deploy your project (2-5 minutes)

### Step 6: Post-Deployment Setup

1. **Success Message**: You'll see "Deployment Successful"
2. **Visit Site**: Click the provided URL (e.g., `https://ai-personalized-learning.vercel.app`)
3. **Test Features**:
   - ✅ Homepage loads
   - ✅ Dashboard accessible
   - ✅ AI Chatbot works
   - ✅ Educational content loads
   - ✅ Lessons display properly

## 🔧 Troubleshooting Common Issues

### Issue 1: Build Fails
**Error**: "Build failed" or "Module not found"
**Solution**:
1. Check if all dependencies are in `package.json`
2. Ensure `next.config.js` is valid
3. Remove `.next` folder from git if present

### Issue 2: Environment Variable Missing
**Error**: "GROQ_API_KEY not configured"
**Solution**:
1. Go to Vercel Dashboard → Your Project → Settings → Environment Variables
2. Add `GROQ_API_KEY` with your actual API key
3. Redeploy the project

### Issue 3: API Routes Not Working
**Error**: 404 on API endpoints
**Solution**:
1. Check if API routes are in `app/api/` directory
2. Ensure proper export syntax in route files
3. Verify environment variables are set

### Issue 4: Chatbot Not Responding
**Error**: "Model decommissioned" or API errors
**Solution**:
1. Verify Groq API key is correct
2. Check if API key has sufficient credits
3. Ensure using supported model in chatbot API

## 📊 Monitoring Your Deployment

### Vercel Dashboard Features:
1. **Analytics**: View visitor statistics
2. **Functions**: Monitor API performance
3. **Logs**: Check for errors
4. **Domains**: Manage custom domains

### Performance Monitoring:
- **Speed Insights**: Automatic performance analysis
- **Core Web Vitals**: Real user metrics
- **Function Logs**: API call monitoring

## 🔄 Continuous Deployment

**Automatic Updates**:
- Every push to `main` branch triggers new deployment
- Preview deployments for pull requests
- Automatic rollback on failures

## 🌐 Custom Domain (Optional)

1. **Add Domain**: Vercel Dashboard → Settings → Domains
2. **Configure DNS**: Follow Vercel's DNS instructions
3. **SSL Certificate**: Automatically provided by Vercel

## 📱 Mobile Optimization

Your app is already mobile-responsive with:
- ✅ Tailwind CSS responsive design
- ✅ Mobile-friendly chat interface
- ✅ Touch-optimized navigation

## 🚀 Performance Optimization

Vercel automatically provides:
- ✅ Global CDN
- ✅ Edge Functions
- ✅ Automatic image optimization
- ✅ Code splitting
- ✅ Caching strategies

## 📞 Support & Resources

### Vercel Support:
- **Documentation**: [vercel.com/docs](https://vercel.com/docs)
- **Community**: [github.com/vercel/vercel/discussions](https://github.com/vercel/vercel/discussions)
- **Status**: [vercel-status.com](https://vercel-status.com)

### Project-Specific Help:
- **GitHub Issues**: [github.com/ashokmedar15/AI-PERSONALIZED-LEARNING/issues](https://github.com/ashokmedar15/AI-PERSONALIZED-LEARNING/issues)
- **README**: Check project documentation

## 🎉 Success Checklist

After deployment, verify:
- ✅ [ ] Homepage loads without errors
- ✅ [ ] Dashboard is accessible
- ✅ [ ] AI Chatbot responds correctly
- ✅ [ ] Educational content loads
- ✅ [ ] Lessons display properly
- ✅ [ ] Mobile responsiveness works
- ✅ [ ] API endpoints return data
- ✅ [ ] Environment variables are set

## 🔗 Your Live URLs

Once deployed, you'll have:
- **Production**: `https://ai-personalized-learning.vercel.app`
- **Preview**: `https://ai-personalized-learning-git-main-username.vercel.app`
- **Custom Domain**: (if configured)

---

**🎯 Ready to deploy? Follow the steps above and your AI-Powered Educational Platform will be live in minutes!**

**Need help?** Check the troubleshooting section or create an issue on GitHub. 