# Install Craft UI

> Craft UI will be installed as a [git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules) and will be placed in your `@/components` folder along with shadcn/ui. To recieve updates make sure to peroidically run
> ```bash
> git submodule init
> git submodule update
> ```
> Alternatively, you can download the folder from releases and place in your components folder.

For examples of Craft UI, check out [craftui.org](https://craftui.org) or this [Repository](https://github.com/9d8dev/craft-examples).

## Create NextJS App With Tailwind 

```bash
npx create-next-app@latest my-app --typescript --tailwind --eslint
```

## Install Dependencies 

```bash
# Install Dependencies
npm install
npm install -D react-wrap-balancer
npm install -D @tailwindcss/typography
npm install -D next-themes
```

## Install Shadcn/ui

```bash
# Install shadcn/ui and all components
npx shadcn-ui@latest init -y
npx shadcn-ui@latest add -a 
```

## Install Craft

```bash
# Install Craft Components
cd components
git submodule add https://github.com/9d8dev/craft
cd ../
```
