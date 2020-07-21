# NubankFrontEnd
Clone front end do app Nubank


Para utilizar esse aplicativo em um sistema android é necessário modificar o arquivo MainActivity.java, adicionando as seguintes linhas:

+ import com.facebook.react.ReactActivityDelegate;
+ import com.facebook.react.ReactRootView;
+ import com.swmansion.gesturehandler.react.RNGestureHandlerEnabledRootView;
 
nos imports e:

+  @Override
+  protected ReactActivityDelegate createReactActivityDelegate() {
+    return new ReactActivityDelegate(this, getMainComponentName()) {
+      @Override
+      protected ReactRootView createRootView() {
+       return new RNGestureHandlerEnabledRootView(MainActivity.this);
+      }
+    };
+  }



Cópia do front end do app Nubank com as animações do app.
