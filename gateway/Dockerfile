FROM nginx:1.22

COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY --from=build /app/build /staticfiles
