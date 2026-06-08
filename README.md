# my-essay
git clone [your-repo-link]
# Create essay with multiple commits
echo "Essay Title: The Impact of Social Media" > essay.txt
git add essay.txt
git commit -m "Add essay title"
git push origin main

echo "Introduction: Social media has changed how we communicate..." >> essay.txt
git add essay.txt
git commit -m "Add introduction paragraph"
git push origin main

echo "Body: Studies show that social media usage..." >> essay.txt
git add essay.txt
git commit -m "Add body paragraph with research"
git push origin main

git log --oneline
git diff HEAD~2 HEAD
