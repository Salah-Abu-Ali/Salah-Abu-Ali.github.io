# Salah — Portfolio Website (Game Developer & Mathematics Educator)

A minimalist, high-contrast monochrome portfolio website crafted for a **Game Developer & Mathematics Educator**. Features real-time interactive physics simulations, vector field kinematics, clean typography, and zero-build deployment ready for **GitHub Pages**.

---

## 🚀 Features

- **Minimalist Monochrome Aesthetics**: Typographically driven, black & white high-contrast editorial design.
- **Interactive Math Hero**: Pure HTML5 vector field / harmonic wave simulation responding to cursor movement.
- **Live Physics Sandbox**: Real-time numerical integration of a damped physical pendulum with interactive bob-dragging, variable gravity, friction, and energy conservation readouts.
- **Project Showcases**: Cards highlighting game engineering (`PuzzleMe`), procedural generation (Delaunay triangulation), and simulation physics.
- **Zero Build Step**: Built with standard modern HTML5, Tailwind CSS CDN, and Lucide icons. Runs directly in any browser and hosts seamlessly on GitHub Pages.

---

## 🌐 How to Host on GitHub Pages (Step-by-Step)

### Option A: Create a Dedicated User Site (`<username>.github.io`)
If your repository is named `<your-username>.github.io`, your portfolio will be hosted directly at `https://<your-username>.github.io/`.

1. **Create the GitHub repository**:
   - Go to [GitHub.com](https://github.com) -> Click **New Repository** (`+` in top right).
   - Name it `<your-username>.github.io` (or `portfolio`).
   - Leave it **Public**.

2. **Push your code from this directory**:
   ```bash
   git init -b main
   git add .
   git commit -m "Initial commit: Portfolio website"
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

3. **Enable GitHub Pages (if using a standard repo name like `portfolio`)**:
   - Go to your repository on GitHub.
   - Navigate to **Settings** &rarr; **Pages** (in the left sidebar).
   - Under **Build and deployment** &rarr; **Source**, select **Deploy from a branch**.
   - Under **Branch**, select `main` and folder `/ (root)`, then click **Save**.
   - Your site will be live within 1–2 minutes at `https://<your-username>.github.io/<repo-name>/`!

---

## 🛠️ Customization

- **Contact Email**: Open [index.html](file:///d:/Salah/Websites/Portfolio/index.html) and search for `contact@salah.dev` to update your email.
- **Social Links**: Update the GitHub and LinkedIn links in the header and footer with your profile URLs.
- **Projects**: Edit or add projects inside the `<section id="projects">` container.
