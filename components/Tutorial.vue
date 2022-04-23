<!-- Please remove this file from your project -->
<template>
  <div
    class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0"
  >
    <link
      href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css"
      rel="stylesheet"
    />
    <div class="max-w-4xl mx-auto sm:px-6 lg:px-8">
      <div class="flex justify-center mt-8">
        <a
          href="https://aws.amazon.com/jp/amplify/"
          target="_blank"
          rel="nofollow noopener"
        >
          <svg
            width="86"
            height="64"
            viewBox="0 0 256 191"
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            preserveAspectRatio="xMidYMid"
          >
            <defs>
              <linearGradient
                id="amplify-linear-gradient"
                x1="100%"
                y1="22.1718317%"
                x2="0%"
                y2="77.8281683%"
              >
                <stop stop-color="#FF9900" offset="0%"></stop>
                <stop stop-color="#FFC300" offset="100%"></stop>
              </linearGradient>
            </defs>
            <g>
              <path
                d="M55.7091852,158.47619 L127.815882,158.47619 L146.285714,190.984127 L145.765368,190.984127 L0,190.984127 L51.3642878,101.977675 L72.8892597,64.7056839 L91.3696717,96.728228 L55.7091852,158.47619 Z M82.6014712,47.8501573 L100.345402,17.1043291 L200.765899,190.983604 L165.203074,190.983604 L82.6014712,47.8501573 Z M110.221481,0 L145.736961,0 L256,190.984127 L220.439804,190.984127 L110.221481,0 Z"
                fill="url(#amplify-linear-gradient)"
              ></path>
            </g>
          </svg>
        </a>
      </div>
      <div class="mt-8 bg-white overflow-hidden shadow sm:rounded-lg p-6">
        <p class="mt-3 text-gray-600">
          このNuxtアプリケーションはSPAモードで<a
            href="https://aws.amazon.com/jp/amplify/"
            target="_blank"
            rel="nofollow noopener"
            class="button--doc text-green-500 hover:underline"
            >AWS Amplify</a
          >を使ってデプロイしています。<br />
          Amplifyを使うと面倒な設定不要でCI/CDを含むオールインワンなデリバリー環境を構築できます。
        </p>
        <p class="mt-4 pt-4 text-gray-800 border-t border-dashed">
          Amplifyを使えば気軽にリリースできますが、代わりにきめ細かい設定はできません。<br />
          特にセキュリティ要件が求められるアプリケーションではCloudFront+S3の構成を検討してください。<br />
          このブログ記事の比較がとても分かりやすいです。
        </p>
        <ul class="pt-4 text-gray-800">
          <li>
            <a
              href="https://go-to-k.hatenablog.com/entry/2021/08/08/022528"
              target="_blank"
              rel="nofollow noopener"
              class="button--doc text-green-500 hover:underline"
              >ConsoleとCloudFront+S3のユースケースの違い - 365歩のテック</a
            >
          </li>
        </ul>
        <p class="mt-4 pt-4 text-gray-800 border-t border-dashed">
          より詳しく知りたい方は<a
            href="https://github.com/waicode/amplify-nuxt-spa-sampl"
            target="_blank"
            rel="nofollow noopener"
            class="button--doc text-green-500 hover:underline"
            >Githubリポジトリ</a
          >の<code class="bg-gray-100 text-sm p-1 rounded border"
            >README.md</code
          >をご覧ください。
        </p>
      </div>
      <div class="flex justify-center pt-8 gap-4 space-x-2">
        <a
          href="https://github.com/waicode/amplify-nuxt-spa-sample"
          target="_blank"
          rel="nofollow noopener"
          ><svg
            class="text-gray-600 hover:text-gray-800 button--github"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            aria-hidden="true"
            role="img"
            width="48"
            height="48"
            preserveAspectRatio="xMidYMid meet"
            viewBox="0 0 24 24"
          >
            <path
              d="M12 2.247a10 10 0 0 0-3.162 19.487c.5.088.687-.212.687-.475c0-.237-.012-1.025-.012-1.862c-2.513.462-3.163-.613-3.363-1.175a3.636 3.636 0 0 0-1.025-1.413c-.35-.187-.85-.65-.013-.662a2.001 2.001 0 0 1 1.538 1.025a2.137 2.137 0 0 0 2.912.825a2.104 2.104 0 0 1 .638-1.338c-2.225-.25-4.55-1.112-4.55-4.937a3.892 3.892 0 0 1 1.025-2.688a3.594 3.594 0 0 1 .1-2.65s.837-.262 2.75 1.025a9.427 9.427 0 0 1 5 0c1.912-1.3 2.75-1.025 2.75-1.025a3.593 3.593 0 0 1 .1 2.65a3.869 3.869 0 0 1 1.025 2.688c0 3.837-2.338 4.687-4.563 4.937a2.368 2.368 0 0 1 .675 1.85c0 1.338-.012 2.413-.012 2.75c0 .263.187.575.687.475A10.005 10.005 0 0 0 12 2.247z"
              fill="currentColor"
            /></svg
        ></a>
        <a
          href="https://twitter.com/waicode37"
          target="_blank"
          rel="nofollow noopener"
          ><svg
            class="text-gray-600 hover:text-gray-800"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            aria-hidden="true"
            role="img"
            width="48"
            height="48"
            preserveAspectRatio="xMidYMid meet"
            viewBox="0 0 24 24"
          >
            <path
              d="M22.46 6c-.77.35-1.6.58-2.46.69c.88-.53 1.56-1.37 1.88-2.38c-.83.5-1.75.85-2.72 1.05C18.37 4.5 17.26 4 16 4c-2.35 0-4.27 1.92-4.27 4.29c0 .34.04.67.11.98C8.28 9.09 5.11 7.38 3 4.79c-.37.63-.58 1.37-.58 2.15c0 1.49.75 2.81 1.91 3.56c-.71 0-1.37-.2-1.95-.5v.03c0 2.08 1.48 3.82 3.44 4.21a4.22 4.22 0 0 1-1.93.07a4.28 4.28 0 0 0 4 2.98a8.521 8.521 0 0 1-5.33 1.84c-.34 0-.68-.02-1.02-.06C3.44 20.29 5.7 21 8.12 21C16 21 20.33 14.46 20.33 8.79c0-.19 0-.37-.01-.56c.84-.6 1.56-1.36 2.14-2.23z"
              fill="currentColor"
            /></svg
        ></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NuxtTutorial',
}
</script>
